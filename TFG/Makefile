MAIN_LATEX=document

BUILD_DIR=obj/
LATEXMK_OPTS="-output-directory=$(BUILD_DIR)"
PDFLATEX_OPTS="--output-directory=$(BUILD_DIR)"

TEX_ENGINE=-pdflatex="pdflatex $(PDFLATEX_OPTS)"

all: latex

mkbuilddir:
	mkdir -p $(BUILD_DIR)

latex:
	latexmk -pdf $(LATEXMK_OPTS) $(TEX_ENGINE) $(MAIN_LATEX).tex
	mv $(BUILD_DIR)/$(MAIN_LATEX).pdf .

clean:
	latexmk $(LATEXMK_OPTS) -c $(MAIN_LATEX).tex
	rm -f *~
	rm -f *.run.xml
	rm -f $(MAIN_LATEX).bbl
