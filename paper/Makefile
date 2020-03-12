doc=main

all: $(doc).pdf

$(doc).pdf: *.tex sections/*.tex figures/*
	pdflatex $(doc).tex
	bibtex $(doc)
	pdflatex $(doc).tex

clean:
	rm -rf $(DOCUMENT).ps *.aux *.toc \
	*.blg *.bbl *.blg *.dvi *.mtc *.mtc? *.maf *.log *.out *.pdf *.ps
