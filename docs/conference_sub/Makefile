#a comment
TEX    = pdflatex
BIBTEX = bibtex
RM     = /bin/rm -rf

TEXT   = recsys

all: paper

paper:
	$(TEX)     $(TEXT).tex
	$(BIBTEX)  $(TEXT)
	$(TEX)     $(TEXT).tex
	$(TEX)     $(TEXT).tex

clean:
	$(RM)  *.dvi  *.log  *.aux  *.blg  *.bbl  *.out *~

clean_all:
	$(RM)  *.dvi  *.log  *.aux  *.blg  *.bbl  *.out *~  *.pdf  *.ps 
