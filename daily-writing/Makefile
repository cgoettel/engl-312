writings.pdf: *.tex Makefile generate-tex.pl
	./generate-tex.pl
	rm -f writings.aux writings.bbl writings.blg writings.brf writings.lof writings.log writings.lot writings.out writings.toc
	xelatex -halt-on-error writings.tex
	xelatex writings.tex

clean: rm -f writings.aux writings.bbl writings.blg writings.brf writings.lof writings.log writings.lot writings.out writings.toc
