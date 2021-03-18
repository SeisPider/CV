SRC = *.tex

all: cv.pdf clean

cv.pdf: $(SRC)
		latexmk -xelatex cv

clean:
		-rm *.xdv *.fls *.log *.out *.aux *.fdb_latexmk

