FROM haggaie/texlive:latest

RUN apt-get update && DEBIAN_FRONTEND=noninteractive apt-get -y --no-install-recommends install \
	latexmk

ENTRYPOINT ["latexmk"]
