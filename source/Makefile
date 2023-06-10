all: print latex web view

jing: *.ptx 
	jing ThirdMill.ptx

pdf: *.ptx Makefile
	pretext build print

latex: *.ptx 
	pretext build print-latex

print: *.ptx Makefile
	pretext build print
#	

web: *.ptx  Makefile
	pretext build web

webview: 
	pretext view web

pdfview: 
	pretext view print


