main.pdf: *.tex Makefile *.jpg
	rm -f main.aux main.bbl main.blg main.brf main.lof main.log main.lot main.out main.toc
	xelatex -halt-on-error main.tex
	xelatex main.tex
	xelatex main.tex

clean:	rm -f main.aux main.bbl main.blg main.brf main.lof main.log main.lot main.out main.toc
