all:
	make clean	
	latexmk -xelatex template.tex
	evince template.pdf
clean:
	-rm template.pdf
	-rm *.log
	-rm *.aux
	-rm *.fls
	-rm *.fdb_latexmk
