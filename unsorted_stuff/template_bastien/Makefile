build :
	pdflatex -shell-escape -draftmode main.tex
	makeindex -s perso.ist main.idx
	bibtex main.aux
	pdflatex -shell-escape -draftmode main.tex
	pdflatex -shell-escape main.tex
