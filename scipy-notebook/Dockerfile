FROM jupyter/scipy-notebook
USER root

# Add support for displaying latex in matplotlib (and not only)
RUN apt-get update && \
    apt-get install -y dvipng texlive-latex-extra texlive-fonts-recommended

# Install nltk
RUN pip install -U nltk

USER $NB_USER
