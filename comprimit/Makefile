# se diu comprimit, no perque estigui comprimit, sino perque abans tenia molts fitxers diferents per fer exactament el mateix

# Observacio, no puc possar aparentment noms ja existents...
exemple-0:
	cd pic; pic -t 000-exemple.pic > concepts.tex
	make compila
objecte-1:
	cd pic; pic -t 001-objectes.pic > concepts.tex
	make compila
arcs-2:
	cd pic; pic -t 002-arcs.pic > concepts.tex
	make compila
resize-3:
	cd pic; pic -t 003-resize.pic > concepts.tex
	make compila
lines-4:
	cd pic; pic -t 004-lines.pic > concepts.tex
	make compila
decoracio-5:
	cd pic; pic -t 005-deco.pic > concepts.tex
	make compila
text-6:
	cd pic; pic -t 006-textPOS.pic > concepts.tex
	make compila
move-7:
	cd pic; pic -t 007-mov.pic > concepts.tex
	make compila

compila: latek clear

latek:
	cd b; latex ../latex/lola.tex; dvipdf lola.dvi; zathura lola.pdf

clear:
	rm -f pic/*.tex
