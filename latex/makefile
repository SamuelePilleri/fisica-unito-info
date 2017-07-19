default: pdf clean

pdf: risposte.tex
	@latexmk -pdf risposte.tex
	@mv risposte.pdf ..

clean:
	@rm -f risposte.aux risposte.blg risposte.dvi risposte.toc risposte.log risposte.out risposte.fls risposte.fdb_latexmk
	@rm -f domande/*.aux domande/*.log
