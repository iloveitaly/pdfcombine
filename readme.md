[poppler-utils looks like the best alternative](https://www.mankier.com/package/poppler-utils)

---

PDFCombine is a simple command line ulitility to combine PDF files.
It uses the PDFKit framework, and thus requires OS X 10.4.x.
Usage is very simple you must specify two or more input files and one output file. Heres an example where I will be combining top.pdf and bottom.pdf and outputting them to final.pdf:

PDFCombine top.pdf bottom.pdf -o final.pdf

The -o argument must be specified before the path of your output file, and after your list of PDF's to combine.

*This application is very old and may not work. Releasing the code in case it's useful to anyone.*
