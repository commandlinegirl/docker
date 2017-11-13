FROM jupyter/scipy-notebook
USER root

# Add support for displaying latex in matplotlib (and not only)
RUN apt-get update && \
    apt-get install -y dvipng texlive-latex-extra texlive-fonts-recommended

# Install nltk
RUN pip install -U nltk

# Install hmmlearn
RUN pip install -U hmmlearn

USER $NB_USER
