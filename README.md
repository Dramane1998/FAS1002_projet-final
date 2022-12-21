# FAS1002_projet-final

[![](https://img.shields.io/badge/Licence-CC%20BY--SA%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by-sa/4.0/deed.fr)

Ce répertoire se veut exemple typique d'un rapport fonctionnel à remettre pour le projet final du cours [FAS1002 - Initiation à la programmation en sciences sociales](https://admission.umontreal.ca/cours-et-horaires/cours/fas-1002/) qui est offert dans le cadre du [Microprogramme de 1er cycle en analyse des mégadonnées en sciences humaines et sociales](https://admission.umontreal.ca/programmes/microprogramme-de-1er-cycle-en-analyse-des-megadonnees-en-sciences-humaines-et-sociales/structure-du-programme/). Par le fait même, ce répertoire est aide en indiquant aux étudiant.e.s permet aux étudiant.e.s qui doivent construire un rapport de toute pièce les éléments à changer en plus d'offrir une structure relativement de base. Il manque certains dossiers cruciaux, mais ils n'y sont pas à des fins éducatives!

## Instructions

1.  Pour démarrer avec ce répertoire, nous avons *fork* ce répertoire.

2.  Ensuite, nous avons activer *GitHub Pages* dans les settings et choisir la *Deploy from a branch* (`gh-pages`). Nous avons ensuite commit tous nos fichiers dans notre repertoire. La page devrait se trouver à **`https://Dramane98.github.io/FAA1002.Projet final/`**.

3.  Egalement nous avons modifier notre section `About` en haut à droite de votre répertoire pour faciliter la visite de votre site web.

4.  Pour commencer à coder le plus rapidement, le plus simple est d'importer le répertoire à travers les menus de RStudio en créant un nouveau `Project >  Version Control > votre répertoire`.

    1.  Pour les plus téméraires, vous pouvez `git clone https://github.com/USERNAME/votre-repertoire` à partir de votre terminal.
    2.  N'oubliez pas de *commit* périodiquement en tenant compte de la fonctionnalité de vos ajouts. Je vous invite à révisiter le guide [GitHub flow](https://docs.github.com/en/get-started/quickstart/github-flow) pour en apprendre davantage.

5.  Enfin, pour mettre à jour notre site web, la façon le plus simple est de *render* notre site localement .Nous avons *commit* nos changements, surtout le dossier `_freeze/` et de *push* le tout sur GitHub.

## Structure du répertoire

``` bash
├── 404.qmd
├── a-propos.qmd
├── assets
│   ├── img
│   │   └── FAS1002.png
│   └── scss
│       ├── styles.css
│       └── styles-dark.scss
├── data
│   ├── processed
│   └── raw
├── exploration.qmd
├── FAS1002_projet-final.Rproj
├── figures
├── _freeze
│   └── ...
│      └── contenu des computations
├── import.qmd
├── index.qmd
├── intro.qmd
├── LICENSE
├── _quarto.yml
├── R
├── README.md
└── references.bib

33 directories, 46 files
```

La quasi-totalité des fichiers seront amenés à être modifiés; ils ne sont que des exemples très, très brefs. Ceux-ci constituent la base de notre rapport.

## Principaux packages R utilisés dans ce site qui sert d'exemple:

-   R Core Team (2020). R: A language and environment for statistical computing. R Foundation for Statistical Computing, Vienna, Austria. <https://www.R-project.org/>

-   H. Wickham. ggplot2: Elegant Graphics for Data Analysis. Springer-Verlag New York, 2016. <https://ggplot2.tidyverse.org>

-   Joe Cheng, Bhaskar Karambelkar and Yihui Xie (2021). leaflet: Create Interactive Web Maps with the JavaScript 'Leaflet' Library. R package version 2.0.4.1. <https://CRAN.R-project.org/package=leaflet>

-   C. Sievert. Interactive Web-Based Data Visualization with R, plotly, and shiny. Chapman and Hall/CRC. Florida, 2020. <https://plotly-r.com>

-   Jennifer Bryan (2017). gapminder: Data from Gapminder. R package version 0.3.0. <https://CRAN.R-project.org/package=gapminder>

## Licence

Cette œuvre est mise à disposition selon les termes de la [licence Creative Commons Attribution - Partage dans les Mêmes Conditions 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/deed.fr).

[![](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](http://creativecommons.org/licenses/by-sa/4.0/deed.fr)
