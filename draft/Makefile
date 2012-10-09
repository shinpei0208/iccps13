TARGET = draft

all:
	latex $(TARGET)
	bibtex $(TARGET)
	latex $(TARGET)
	latex $(TARGET)
	dvips -t letter -o $(TARGET).ps $(TARGET).dvi
	ps2pdf $(TARGET).ps
	#dvipdf draft.dvi

clean:
	rm -fr *~ *.out *.aux *.ps *.pdf *.dvi *.log *.bbl *.blg *.ent
