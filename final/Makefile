TARGET = final

all:
	latex $(TARGET)
	bibtex $(TARGET)
	latex $(TARGET)
	latex $(TARGET)
	#dvips -t letter -o $(TARGET).ps $(TARGET).dvi
	#ps2pdf $(TARGET).ps
	dvipdfmx -p letter final.dvi

clean:
	rm -fr *~ *.out *.aux *.ps *.dvi *.log *.bbl *.blg *.ent
