TARGET=PINNs.pdf

all: $(TARGET)

PINNs.pdf: NNs.pdf

%.pdf: %.tex
	pdflatex $^

clean:
	rm -rf *.log *.aux *.pdf
