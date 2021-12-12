all: final.pdf

final.pdf: final.tex clean
	-pdflatex --shell-escape final.tex
	-pdflatex --shell-escape final.tex
	$(MAKE) clean
	cp final.pdf ../final.pdf

clean:
	rm -f *.aux *.blg *.log *.bbl *.toc *.out *.bcf *.xml *.gz
	rm -rf _minted-*
