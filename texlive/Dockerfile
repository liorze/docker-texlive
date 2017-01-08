FROM debian:jessie

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get -y --no-install-recommends install \
	biber \
	texlive-bibtex-extra \
	texlive-latex-recommended \
	texlive-font-utils \
	texlive-fonts-recommended \
	texlive-latex-extra \
	texlive-generic-recommended \
	texlive-science \
	ghostscript

WORKDIR /document
