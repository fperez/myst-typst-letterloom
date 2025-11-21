.PHONY: all clean

exports/letter.pdf: letter.md
	myst build letter.md

clean:
	rm -rf _build && rm -f exports/letter.pdf

all: exports/letter.pdf
