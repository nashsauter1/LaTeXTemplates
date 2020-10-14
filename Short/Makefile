BUILDDIR=build
FILENAME=paper

pdf:
	mkdir -p $(BUILDDIR)
	pandoc $(FILENAME).md \
		--filter pandoc-citeproc \
		--from=markdown+raw_tex \
		--to=latex \
		--output=$(BUILDDIR)/$(FILENAME).pdf \
		--pdf-engine=xelatex
