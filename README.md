# FYP Documentation

To compile the document using the template

Install:
	- pandoc
	- LaTeX
	- wandmalfarbe/pandoc-latex-template

Then run:
```sh
$ pandoc notes.md -o report.pdf --from markdown --template eisvogel --table-of-contents --highlight-style my_style.theme -V fontsize=10pt

```
