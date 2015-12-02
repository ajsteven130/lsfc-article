all:
	pdflatex -file-line-error ./tex/{{cookiecutter.article_slug}}.tex
	bibtex ./tex/{{cookiecutter.article_slug}}
	bibtex ./tex/{{cookiecutter.article_slug}}	
	pdflatex -file-line-error ./tex/{{cookiecutter.article_slug}}.tex
	bibtex ./tex/{{cookiecutter.article_slug}}	
	pdflatex -file-line-error ./tex/{{cookiecutter.article_slug}}.tex

make install:
	conda update conda
	conda env create

