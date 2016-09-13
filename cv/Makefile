TEXSRC := cv.tex
AUX := $(TEXSRC:.tex=.aux)
PDF := $(TEXSRC:.tex=.pdf)

all:
	pdflatex $(TEXSRC)
	\rm -f *.aux *.log *.bbl *.blg 

clean:
	\rm -f *.aux *.log *.bbl *.blg *.pdf 


