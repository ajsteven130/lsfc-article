all:
	cd ./tex && pdflatex -file-line-error {{cookiecutter.article_slug}}.tex
	cd ./tex && bibtex {{cookiecutter.article_slug}}
	cd ./tex && bibtex {{cookiecutter.article_slug}}
	cd ./tex && pdflatex -file-line-error {{cookiecutter.article_slug}}.tex
	cd ./tex && bibtex {{cookiecutter.article_slug}}
	cd ./tex && pdflatex -file-line-error {{cookiecutter.article_slug}}.tex

make install:
	conda update conda
	conda env create

