BUILDDIR=build
FILENAME=paper

pdf:
	mkdir -p $(BUILDDIR)
	pandoc $(FILENAME).md \
		--from=markdown \
		-t beamer \
		--output=$(BUILDDIR)/$(FILENAME).pdf \
		--pdf-engine=xelatex
