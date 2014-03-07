goettel-resume.pdf: *.tex Makefile
	rm -f *.aux
	pdflatex -halt-on-error goettel-resume.tex
	pdflatex goettel-resume.tex
	pdflatex -halt-on-error cover-letter.tex
	pdflatex cover-letter.tex
	pdflatex -halt-on-error reflection.tex
	pdflatex reflection.tex
