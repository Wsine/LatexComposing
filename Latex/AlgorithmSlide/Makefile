all: algorithmSlide.pdf clean view

algorithmSlide.pdf: algorithmSlide.tex
	xelatex $<

clean:
	rm -f algorithmSlide.aux
	rm -f algorithmSlide.out
	rm -f algorithmSlide.log
	rm -f algorithmSlide.toc
	rm -f algorithmSlide.nav
	rm -f algorithmSlide.snm

view:
	SumatraPDF algorithmSlide.pdf

.PHONY: all view clean