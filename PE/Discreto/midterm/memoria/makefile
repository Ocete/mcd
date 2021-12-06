all: midterm.pdf

midterm.pdf: midterm.tex clean
	-pdflatex --shell-escape midterm.tex
	$(MAKE) clean
	cp midterm.pdf ../midterm.pdf

clean:
	rm -f *.aux *.blg *.log *.bbl *.toc *.out *.bcf *.xml *.gz
	rm -rf _minted-*
