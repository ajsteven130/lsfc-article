all:
	PDFlatex ./tex/{{cookiecutter.article_slug}}.tex
	bibtex ./tex/{{cookiecutter.article_slug}}.tex
	PDFlatex ./tex/{{cookiecutter.article_slug}}.tex

make install:
	conda update conda
	conda env create

