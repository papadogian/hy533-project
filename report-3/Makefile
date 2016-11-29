report:
	cp -p figs/manousos_*/* .
	pdflatex report
	bibtex report
	pdflatex report
	pdflatex report

clean:
	rm -rf *.aux *.bbl *.blg *.log *.out 
	rm -rf *.PNG *.JPG
	rm -rf report.pdf

