## :information_source: Introduction

The goal of this template is to provide a nice-looking poster layout, easy to configure and fill in.

> This poster template is a largely inspired but a purified version of [this template](https://github.com/UCL-INMA/ICTEAMposter).
> 
> Credits to:
> - The [Computational Pysics and Biophysics Group at Jacobs University](http://ukleinekat.user.jacobs-university.de/) for creating the [poster template](https://teamwork.jacobs-university.de:8443/confluence/display/CoPandBiG/LaTeX+Poster)
> - [Nathaniel Johnston](https://www.nathanieljohnston.com) for the [enhanced template](https://www.nathanieljohnston.com/2009/08/latex-poster-template/)
> - [Benoît Legat](https://blegat.github.io/) for the [ICTEAM poster beamer style](https://github.com/UCL-INMA/ICTEAMposter)

Here is an example preview for the header page, table of content, and other main document items:

<p align="center"><img src="https://raw.githubusercontent.com/dhondta/tex-poster-template/master/doc/preview.png" width="35%">


## :card_file_box: Structure

The template is structured in the following way:

- `main.tex`: This is the main TeX file to be compiled. Here you can include your payload.
- `fonts`: This folder contains the fonts to be used in `main.tex`.
- `imgs`: This folder is aimed to contain logos and figures.
- `parts`: This folder contains the bibliography (in BibTeX format) to be used in `main.tex`.
- `styles`: This folder contains the styles for defining the layout. Most of the included ones should not be edited.

## :gear: Compilation

The compilation can easilly be configured in [Texmaker](https://en.wikipedia.org/wiki/Texmaker) by defining a *Quick Build Command*:

1. Go to the menu *Options*
2. Select *Configure Texmaker*
3. Go to tab *Quick Build*
4. In the field *User : (...)*, replace the command with:

        latexmk -pdf -xelatex -use-make %.tex

5. Then click *OK*

This will produce `main.pdf`.

## :newspaper: Making your poster

Parts that you should adapt:

- `main.tex`
- `parts/bibliography.bib`
- include images in `imgs` and refer to these in `main.tex`


## :star: Related Projects

You may also like these:

- [TeX Book Template](https://github.com/dhondta/tex-book-template): A template for writing a nice book with LaTeX.
- [TeX Course Index Template](https://github.com/dhondta/tex-course-index-template): A template for writing a condensed course index leveraging LaTeX indexing.
- [TeX Master Thesis Template](https://github.com/dhondta/tex-master-thesis-template): A template for writing a nice master thesis dissertation with LaTeX.


## :clap: Supporters

[![Stargazers repo roster for @dhondta/tex-poster-template](https://reporoster.com/stars/dark/dhondta/tex-poster-template)](https://github.com/dhondta/tex-poster-template/stargazers)

[![Forkers repo roster for @dhondta/tex-poster-template](https://reporoster.com/forks/dark/dhondta/tex-poster-template)](https://github.com/dhondta/tex-poster-template/network/members)

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

