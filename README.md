# Marq_Phd_Dissertation_Template
This is the repository of Marquette MSSC PhD Dissertation Latex Template. 

# Notice
XeLaTex compiler should be used for this template.

# Fonts setup
You should put your own fonts.ttf files inside ./Fonts/ folder in order to use the template.

Below is an quick example including [Times Fonts](https://cs.fit.edu/code/projects/ndworld/repository/revisions/10/show/Resources/Fonts) in the template.

```
\usepackage{fontspec}
\setmainfont[
Path = ./Fonts/,
BoldFont=timesbd.ttf,
ItalicFont=timesi.ttf,
BoldItalicFont=timesbi.ttf
]{times.ttf}
```
