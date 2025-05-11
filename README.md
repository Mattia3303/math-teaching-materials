# Math Teaching Materials
This repository contains slides about mathematical methods and concepts.  
**They are written in Italian** because I created them for my students.  
If you are not Italian but would like to use them, ask AI to translate them.

The slides currently available are:

* `Factoring Quadratic Polynomials`
* `Factoring All Kinds of Polynomials`

## Generate a PDF from a Markdown File
If you have modified or created a Markdown file and want to convert it to a PDF, follow these simple steps:

1. Download the **Pandoc** document converter from its [GitHub page](https://github.com/jgm/pandoc/releases/tag/3.6.4).
2. Open a terminal and navigate to the folder containing the file you want to convert.
3. For ***Windows*** users, use the following command to convert the file:
    ```cmd
    pandoc "InputFile.md" -o "OutputFile.pdf" --pdf-engine=xelatex
    ```

    For users of other operating systems, try the same command or search online for the appropriate syntax.