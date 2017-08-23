FROM debian:jessie

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get -y --no-install-recommends install \
	biber \
	lmodern \
	texlive-bibtex-extra \
	texlive-latex-recommended \
	texlive-font-utils \
	texlive-fonts-recommended \
	texlive-fonts-extra \
	texlive-latex-extra \
	texlive-lang-arabic \
	texlive-generic-recommended \
	texlive-publishers \
	texlive-science \
	texlive-lang-other \
	texlive-xetex \
	ghostscript \
  && rm -rf /var/lib/apt/lists/* \
  && curl https://downloads.sourceforge.net/project/ivritex/culmus-latex/culmus-latex-0.7/culmus-latex_0.7-1_all_fixed.deb \
  && dpkg -i culmus-latex_0.7-1_all_fixed.deb \
  && rm culmus-latex_0.7-1_all_fixed.deb

WORKDIR /document
