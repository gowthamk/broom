all:
	pdflatex broom
	pdflatex broom
	pdflatex -shell-escape broom
	pdflatex -shell-escape broom
	bibtex broom
	bibtex broom
	pdflatex -shell-escape broom
	bibtex broom
	pdflatex -shell-escape broom

haste:
	pdflatex broom
	open broom.pdf

clean:
	rm *.log *.aux *.bbl
