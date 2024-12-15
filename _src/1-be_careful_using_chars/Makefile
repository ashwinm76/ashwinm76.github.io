INPUT = be_careful_using_chars.tex
OUTPUT = $(INPUT:.tex=.pdf)
STYFILE = ../sty/cpp_advice.sty

all: $(OUTPUT)

clean:
	@latexmk -C 
	@rm -f *.bbl *.cpt *.aux *.fdb_latexmk *.fls *.log

install:
	@mv $(OUTPUT) ../../assets/pdf/

%.pdf: %.tex $(STYFILE)
	@latexmk -pdf $<
