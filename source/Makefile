all: print latex web view

jing: *.ptx 
	jing ThirdMill.ptx

pdf: *.ptx Makefile
	pretext build print

latex: *.ptx 
	pretext build print-latex

print: *.ptx Makefile
	pretext build print
#	pretext view print

web: *.ptx  Makefile
	pretext build web

webview: *.ptx  Makefile
	pretext build web
	pretext view web

viewpdf: print
	evince ../output/print/main.pdf

clean: 
