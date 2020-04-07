# Book
Shared book explaining how the world works based on the ideas mostly associated with free-market economists Ludwig von Mises and 1974 Nobel Laureate in Economics F.A. Hayek


Current versions in <a href="./books/Book.pdf" target="_blank">PDF</a> and in <a href="./books/main_econ_only.md" target="_blank">markdown</a>



To contribute and "assemble" the books you need the following.

Python and install [the markdown preprocessor](https://github.com/jreese/markdown-pp)

pip install MarkdownPP

From the books directory run:

markdown-pp main_econ_only.mdpp -o main_econ_only.md -e latexrender

which will process the main_econ_only.mdpp and create main_econ_only.md

See how the .mdpp file is mostly references to "snippets"


