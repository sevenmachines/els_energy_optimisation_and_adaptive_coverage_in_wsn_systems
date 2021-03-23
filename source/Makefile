DOCNAME="els_energy_optimisation_and_adaptive_coverage_in_wsn_systems"

all: build

.PHONY: clean

build:
	pdflatex $(DOCNAME).tex 
	bibtex $(DOCNAME).aux
	pdflatex $(DOCNAME).tex
	pdflatex $(DOCNAME).tex

view: build
	open $(DOCNAME).pdf

clean: rm *.blg *.bbl *.aux *.log

