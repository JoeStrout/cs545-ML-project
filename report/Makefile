cs545final.pdf: cs545final.tex cs545final.bib
	pdflatex cs545final
	bibtex cs545final
	pdflatex cs545final
	pdflatex cs545final
	open cs545final.pdf

clean:
	rm -f *.aux
	rm -f *.bbl
	rm -f *.blg
	rm -f *.log
	rm -f *.toc
	rm -f cs545final.pdf
	