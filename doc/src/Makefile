LATEX=pdflatex
DELETE=rm -f
MAIN=printer.tex

SRC= $(wildcard $(SRCFOLDER)/*.tex)
TARGET= $(MAIN:.tex=.pdf)

TARGET: $(SRC)
	$(LATEX) -output-directory ../. $(MAIN)

clean:
	$(DELETE) ../printer.aux
	$(DELETE) ../printer.log

mrproper: clean
	$(DELETE) ../printer.pdf
