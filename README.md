# Open Source Project for Quick and Collaborative Creation of Economic Education Books/Articles

This repo is a collection of short markdown files that can be small articles or sections of articles which can then be combined to create larger articles or entire books.

Books in progress are (branch):

1. Why I'm Voting For Jo Jorgensen: The First Female and Economically Woke President of the United States (jojo)
2. The Primary Civic Duty: Economics for Citizens (master)
3. Mises and Hayek or Bust: Avoiding Extinction by Economic Ignorance [Coronavirus ed.] (master)


epub versions of books can be found in /books directory

To contribute and "assemble" the books you need the following.

Python and install [the markdown preprocessor](https://github.com/jreese/markdown-pp)

pip install MarkdownPP

From the books directory run:

markdown-pp main.mdpp -o main.md -e latexrender

which will process the main.mdpp and create main.md

See how the .mdpp file is mostly references to "snippets"

Also install https://pandoc.org/  to convert markdown to html

pandoc main.md -f markdown -t html -o main.html




