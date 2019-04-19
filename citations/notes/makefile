#
# Makefile for references notes
#

## Location of working bibliography file
BIB = "../references.bib"
CSL = ../csl/icesjms.csl

## All markdown files in the working directory
DONEDIR = notes_processed
SRC = $(wildcard *.md)
NEW = $(patsubst %.md, $(DONEDIR)/%.md, $(SRC))

.PHONY : all

all : $(NEW)

$(DONEDIR) :
ifdef $(DONEDIR)
	echo "It exists"
else
	mkdir $(DONEDIR)
endif

$(DONEDIR)/%.md : %.md $(DONEDIR)
	pandoc -standalone --bibliography=$(BIB) --csl=$(CSL) --filter pandoc-citeproc --from markdown --to markdown_github $< -o $@
