main:=report

all: ${main}.pdf

%.pdf: %.tex
	pdflatex $<
	pdflatex $<
	pdflatex $<

clean: clean_keep_pdf
	rm -f *.pdf

clean_keep_pdf:
	rm -f *.toc *.aux *.log

.PHONY: clean clean_keep_pdf
