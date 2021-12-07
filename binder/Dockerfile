FROM mambaorg/micromamba

COPY binder/environment.yml /environment.yml

RUN micromamba install -y -n base -f /environment.yml
