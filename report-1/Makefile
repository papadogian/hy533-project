report:
	cp -p figs/* .
	pdflatex report
	bibtex report
	pdflatex report
	pdflatex report

clean:
	rm -rf *.aux *.bbl *.blg *.log *.out 
	rm -rf *.PNG
	rm -rf report.pdf

