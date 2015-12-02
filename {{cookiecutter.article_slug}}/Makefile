all:
	latex ./tex/{{cookiecutter.article_slug}}.tex
	bibtex ./tex/{{cookiecutter.article_slug}}.tex
	pdflatex ./tex/{{cookiecutter.article_slug}}.tex

make install:
	conda update conda
	conda env create

