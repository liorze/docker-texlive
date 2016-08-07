# Usage
Run `latexmk` with `pdflatex` for example with:
```
    docker run --rm -v ${PWD}:/document haggaie/latexmk pdflatex -latex=pdflatex -pdf <basename>
```

# Credits
Inspired by [thubo/docker-latexmk](https://github.com/Thubo/docker-latexmk).
