INPUT = a_tale_of_two_unions.tex
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
