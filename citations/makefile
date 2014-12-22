#
# Makefile for references notes
#

## Location of working bibliography file
BIB = "c:/Users/kelli/Google Drive/references/references.bib"
CSL = csl/icesjms.csl
# all: refs.bib topics.md
# all: topics.md

topics.md: _topics.md
	pandoc -S --atx-headers --bibliography=$(BIB) --csl=$(CSL) -t markdown_github $< -o $@