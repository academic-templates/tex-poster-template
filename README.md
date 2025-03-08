<h1 align="center">LaTeX Poster Template <a href="https://twitter.com/intent/tweet?text=LaTeX%20Poster%20Template.%0D%0ALaTeX%20template%20for%20designing%20your%20attractive%20poster%2e%0D%0A&hashtags=TeXLaTeX"><img src="https://img.shields.io/badge/Tweet--lightgrey?logo=twitter&style=social" alt="Tweet" height="20"/></a></h1>

## :information_source: Introduction

The goal of this template is to provide a nice-looking poster layout, easy to configure and fill in.

> This poster template is a largely inspired but purified version of [this template](https://github.com/UCL-INMA/ICTEAMposter).
> 
> Credits to:
> - The [Computational Pysics and Biophysics Group at Jacobs University](http://ukleinekat.user.jacobs-university.de/) for creating the [poster template](https://teamwork.jacobs-university.de:8443/confluence/display/CoPandBiG/LaTeX+Poster)
> - [Nathaniel Johnston](https://www.nathanieljohnston.com) for the [enhanced template](https://www.nathanieljohnston.com/2009/08/latex-poster-template/)
> - [Benoît Legat](https://blegat.github.io/) for the [ICTEAM poster beamer style](https://github.com/UCL-INMA/ICTEAMposter)

Here is an example preview:

<p align="center"><img src="https://raw.githubusercontent.com/academic-templates/tex-poster-template/main/doc/preview.png" width="35%"><br>
<sub><sup>Preview image generated with <a href="https://gist.github.com/dhondta/f57dfde304905644ca5c43e48c249125">this tool</a></sup></sub></p>


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

- [TeX Book Template](https://github.com/academic-templates/tex-book-template): A template for writing a nice book with LaTeX.
- [TeX Cheat Sheet Template](https://github.com/academic-templates/tex-cheat-sheet-template): A template for creating a nice cheat sheet with LaTeX.
- [TeX Course Index Template](https://github.com/academic-templates/tex-course-index-template): A template for writing a condensed course index leveraging LaTeX indexing.
- [TeX Master Thesis Template](https://github.com/academic-templates/tex-master-thesis-template): A template for writing a nice master thesis dissertation with LaTeX.
- [TeX Slideshow Template](https://github.com/academic-templates/tex-slideshow-template): A template for making a nice presentation with LaTeX.


## :clap: Supporters

[![Stargazers repo roster for @academic-templates/tex-poster-template](https://reporoster.com/stars/dark/academic-templates/tex-poster-template)](https://github.com/academic-templates/tex-poster-template/stargazers)

[![Forkers repo roster for @academic-templates/tex-poster-template](https://reporoster.com/forks/dark/academic-templates/tex-poster-template)](https://github.com/academic-templates/tex-poster-template/network/members)

<p align="center"><a href="#"><img src="https://img.shields.io/badge/Back%20to%20top--lightgrey?style=social" alt="Back to top" height="20"/></a></p>

