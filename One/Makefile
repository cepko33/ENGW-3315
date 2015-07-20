pdf: project1.md
	pandoc -S --template=template.tex -o output.pdf --filter pandoc-citeproc project1.md; evince output.pdf
doc: project1.md
	pandoc -S -o output.docx --filter pandoc-citeproc project1.md; libreoffice output.docx
