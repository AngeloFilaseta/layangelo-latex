# layangelo-latex

## Commands

### Images
``\centeredImage{#1}{#2}{#3}`` is used to place and center an image. Place the image path as ``#1``, the caption as ``#2``, and a number between 0 and 1 in ``#3`` to specify the widht.

### Highliting
``\hly{text}`` and ``\hlY{text}`` are the commands used to highlight.
Both use the stock yellow highlighter, but ``\hlY{text}`` is a bit darker.

### Enviroments
#### File
Usage:
```md
\begin{file}[optional filename, defaults to "File"]
	File contents, for example, with a listings environment
\end{file}
```
#### Info
Usage:
```md
\begin{info}[optional title, defaults to "Info:"]
	Some info
\end{info}
```
#### Question
Usage:
``` md
\begin{question}[optional title]
	Question contents
\end{question}
```

#### Warning
Usage:
```md
\begin{warn}[optional title, defaults to "Warning:"]
	Some Warning
\end{warn}
```

## License
This template originates from [LaTeXTemplates](http://www.LaTeXTemplates.com)

#### Started from:
__Lachaise Assignment__
Original Authors:

- Marion Lachaise
- François Févotte

Vel (vel@LaTeXTemplates.com)

Changes from the original template are listed in the ```layout.tex``` file.

[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2FAngeloFilaseta%2Flayangelo-latex.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2FAngeloFilaseta%2Flayangelo-latex?ref=badge_shield)
