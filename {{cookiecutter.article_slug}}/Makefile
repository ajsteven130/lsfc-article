all:
	cd ./tex && pdflatex -file-line-error {{cookiecutter.article_slug}}.tex
	cd ./tex && bibtex {{cookiecutter.article_slug}}
	cd ./tex && bibtex {{cookiecutter.article_slug}}
	cd ./tex && pdflatex -file-line-error {{cookiecutter.article_slug}}.tex
	cd ./tex && bibtex {{cookiecutter.article_slug}}
	cd ./tex && pdflatex -file-line-error {{cookiecutter.article_slug}}.tex
	cd ./tex && cygstart {{cookiecutter.article_slug}}.pdf

make install:
	conda update conda
	conda env create

view:
	cd ./tex && cygstart {{cookiecutter.article}}.pdf

clean:
	cd ./tex && rm *.aux
	cd ./tex && rm *.blg
	cd ./tex && rm *.log
	cd ./tex && rm *.bbl
	cd ./tex && rm *.out
	cd ./tex && rm *.toc
