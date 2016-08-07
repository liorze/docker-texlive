FROM debian:jessie

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get -y --no-install-recommends install \
	texlive-latex-recommended \
	texlive-font-utils \
	texlive-fonts-recommended \
	texlive-latex-extra \
	texlive-generic-recommended \
	ghostscript

WORKDIR /document
