# Marq Phd Dissertation LaTex Template
This is the repository of Marquette University MSSC PhD Dissertation Latex Template. 

# Before start
**XeLaTex** compiler should be used for this template.

# Fonts setup
You should put your own fonts.ttf files inside **./Fonts/** folder and set fonts in **main.tex** in order to make everything works.

Below is an quick example including [Times Fonts](https://cs.fit.edu/code/projects/ndworld/repository/revisions/10/show/Resources/Fonts) in the template.

```latex
\usepackage{fontspec}
\setmainfont[
Path = ./Fonts/,
BoldFont=timesbd.ttf,
ItalicFont=timesi.ttf,
BoldItalicFont=timesbi.ttf
]{times.ttf}
```
