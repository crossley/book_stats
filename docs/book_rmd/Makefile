# Define the default make target
all: book

# Target to compile the Bookdown book
book:
	Rscript -e "bookdown::render_book('index.Rmd', 'bookdown::gitbook')"

# Target to clean up intermediate files
clean:
	rm bookdown_files.Rmd
	rm -rf _bookdown_files
	rm -rf book_html

.PHONY: all book clean

