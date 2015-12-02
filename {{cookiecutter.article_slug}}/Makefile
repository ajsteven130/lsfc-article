all:
	latex {{cookiecutter.article_slug}}.tex
	bibtex {{cookiecutter.article_slug}}.tex
	pdflatex {{cookiecutter.article_slug}}.tex

make install:
	conda update conda
	conda env create

