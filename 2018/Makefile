EXE=2018.pdf
SRC=2018.tex
BIB=2018.aux

$(EXE):$(SRC)
	xelatex $(SRC)

.PHONY.:look
look:
	evince 2018.pdf

.PHONY.:clean
clean:
	$(RM) 2018.aux 2018.log 2018.pdf 2018.dvi 2018.bbl 2018.blg 2018.toc 2018.out 2018.nav 2018.snm 2018.thm 2018.lot 2018.lof
