# migurdia

Semantic-based LaTeX resume template.

Migurdia aims at creating a resume template whose body is entirely free of formatting and styling except those specifically specified by the user. All sections and data groups are customized through key-value arguments and can be used or interpreted with ease.

![](assets/preview.png)

## Usage

XeLaTeX is required for using migurdia.

Create a new LaTeX document aside `migurdia.tex` in the same directory, copy the template into that file and you can start typesetting your resume right away.

If you are using Overleaf, remember to:

* set your *compiler* in the *menu* to *XeLaTeX*
* ensure that the *main document* is *not* `migurdia.tex`

If you wish to enable CJK character support, you would have to uncomment certain sections in `migurdia.tex` in order to have them shown naturally.
