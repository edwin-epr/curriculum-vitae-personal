FILENAME=edwin-cv

all:
	latexmk -pdf $(FILENAME).tex

clean:
	latexmk -c $(FILENAME).tex

cleanAll:
	latexmk -C $(FILENAME).tex 

.PHONY= all clean cleanAll
