SHEETS = \
	sheet01.pdf

sheet%.pdf: sheet%.tex
	pdflatex sheet$*.tex
	pdflatex sheet$*.tex

all: $(SHEETS)
