DOC=presentation

all:
	pdflatex $(DOC).tex
	#bibtex $(DOC).aux	
	pdflatex $(DOC).tex
	pdflatex $(DOC).tex
	#evince $(DOC).pdf &

clean:
	rm *.log *.aux *.nav *.out *.snm *.toc 
