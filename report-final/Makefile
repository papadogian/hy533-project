report:
	cp -p figs/manousos_*/* .
	cp -p figs/mockups/* .
	cp -p figs/phase1/* .
	pdflatex report
	bibtex report
	pdflatex report
	pdflatex report

clean:
	rm -rf *.aux *.bbl *.blg *.log *.out 
	rm -rf *.PNG *.JPG *.jpg
	rm -rf report.pdf

