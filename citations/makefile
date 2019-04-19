#
# Makefile for references notes
#

## Location of working bibliography file
BIB = "references.bib"
CSL = csl/icesjms.csl

## Notes
MAKE = notes/makefile
MAKEDIR = notes_processed
MAKENAME = make

all : $(MAKEDIR) topics.md EBFMIndicators.md

$(MAKEDIR) :
	cd notes && $(MAKENAME)

topics.md : _topics.md
	pandoc -S --atx-headers --bibliography=$(BIB) --csl=$(CSL) -t markdown_github $< -o $@

EBFMIndicators.md : _EBFMIndicators.md
	pandoc -S --atx-headers --bibliography=$(BIB) --csl=$(CSL) -t markdown_github $< -o $@
