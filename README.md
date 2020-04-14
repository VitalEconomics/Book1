# Book


Open Source book explaining how the world works based on the ideas mostly associated with free-market economists Ludwig von Mises and 1974 Nobel Laureate in Economics F.A. Hayek with additional content dealing with Coronavirus. Kindle version updated every week or two.

Current versions in <a href="./books/Book.pdf" target="_blank">PDF</a> in <a href="./books/main.md" target="_blank">markdown</a> and <a href="./books/main.html" target="_blank">html</a>


To contribute and "assemble" the books you need the following.

Python and install [the markdown preprocessor](https://github.com/jreese/markdown-pp)

pip install MarkdownPP

From the books directory run:

markdown-pp main.mdpp -o main.md -e latexrender

which will process the main.mdpp and create main.md

See how the .mdpp file is mostly references to "snippets"

Also install https://pandoc.org/  to convert markdown to html

pandoc main.md -f markdown -t html -o main.html




