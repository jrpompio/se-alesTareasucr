all: tex

MAIN = B97026Quiz1

tex: 
	pdflatex -shell-escape $(MAIN).tex
	
clean:
	rm $(MAIN).aux $(MAIN).log $(MAIN).out &
	rm -r _minted-$(MAIN) &