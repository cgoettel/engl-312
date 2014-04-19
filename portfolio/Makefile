reflection.pdf: *.tex Makefile
	rm -f reflection.aux reflection.bbl reflection.blg reflection.brf reflection.lof reflection.log reflection.lot reflection.out reflection.toc
	pdflatex -halt-on-error reflection.tex
	pdflatex reflection.tex

clean:	rm -f *.aux *.bbl *.blg *.brf *.lof *.log *.lot *.out *.toc
