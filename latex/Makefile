texname = harjoitustyo

tyoselostus: $(texname).tex $(wildcard *.tex) $(wildcard *.bib)
	rubber --pdf $(texname).tex

clean: $(texname).tex
	rubber --clean $(texname).tex
