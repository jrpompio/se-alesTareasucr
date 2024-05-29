all: tex

MAIN = B97026TareaBloques

tex: 
	pdflatex -shell-escape $(MAIN).tex
	make clean

clean:
	rm $(MAIN).aux $(MAIN).log $(MAIN).out &
	rm -r _minted-$(MAIN) &