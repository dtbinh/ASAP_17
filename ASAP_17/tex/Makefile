NAME = MPC

all:$(NAME).pdf

$(NAME).pdf: *.tex	*.bib ../figure/*.pdf
	#pdflatex $(NAME)
	pdflatex $(NAME)
	bibtex $(NAME)
	pdflatex $(NAME)
	pdflatex $(NAME)

clean:
	rm -f $(NAME).aux $(NAME).bbl $(NAME).dvi $(NAME).blg $(NAME).ps $(NAME).out *log *~

