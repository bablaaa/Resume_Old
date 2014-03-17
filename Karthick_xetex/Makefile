TEXFILES=cv-commands.tex simplemargins.sty
IMAGES=bike.jpg gnu.png hack.png idea.jpg

TARGET=Karthick.pdf

all: $(TARGET)

%.pdf: %.tex $(TEXFILES) $(IMAGES)
	xelatex $<

clean:
	rm -f *.log *.aux $(TARGET)
