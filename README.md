# thesis
Backup for my thesis LaTeX project.

This repo contains the LaTeX project of my Masters thesis.
The main file that needs to be compiled with pdflatex is Masterarbeit.tex.

There is and additional nomenclature nlo file which needs to be made with the command line call
`makeindex Masterarbeit.nlo -s nomencl.ist -o Masterarbeit.nls`.
Afterwards, the texfile needs to be compiled twice to incorporate changes made to the nomenclature.

All images are in the img/ subdirectory.

There is a default citation style using the Literatur.bib file, and there is (currently commented out
in the .tex file) an extensive APA version, which requires:
- Default bibliography tool biber (configuration change)
- Masterarbeit.bib (to be commented out in .tex)
- compilation of bib-file twice, then one compilation of .tex file
- biber > 2.7

Feel free to clone and use the template for your own projects!
Cheers
