all: compile compile_bib compile_2 clean

compile: Tesi.tex
	pdflatex Tesi
compile_2: Tesi.tex 
	pdflatex Tesi
	pdflatex Tesi
compile_bib: Bibliografia.bib
	biber Tesi

.PHONY: clean
clean:
	rm *.toc
	rm *.xml
	rm *.out
	rm *.log
	rm *.bcf
	rm *.aux
	rm *.blg
	rm *.bbl


