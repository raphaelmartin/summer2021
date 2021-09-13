---
title: "Stratégies Numériques en Sciences Sociales"
author: "CSS @ CREST"
lang: "fr"
documentclass: article
fontsize: 12pt
papersize: a4
geometry: margin=2cm
mainfont: NewComputerModern
mathfont: NewComputerModern Math
colorlinks: true
linkcolor: blue
urlcolor: blue
header-includes:
  - \usepackage{hyperref}
  - \hypersetup{colorlinks=true,linkcolor=blue,urlcolor=blue}
...

# Stratégies Numériques en Sciences Sociales

Ce cours part d’un constat : nous sommes de plus en plus entourés de données numériques. Dans le débat public, dans notre quotidien, dans la décision publique, et parfois jusque dans notre vie privée, des traces numériques enregistrent nos activités.

Cette abondance de données est déjà largement analysée par les sciences sociales. Elle est aussi utilisée, afin de poser des questions nouvelles, ou de reposer d’anciennes questions à partir de ces nouvelles sources.

L’enjeu de ce cours, c’est d’offrir à des étudiantes, des jeunes chercheuses qui n’ont pas forcément de compétences en informatique des éléments pour qu’elles puissent d’une part saisir certains des enjeux que pose la multiplication des données numériques, et d’autre part pour qu’elles puissent en tirer partie de façon empirique, en maitrîsant différents outils qui permettent de travailler à partir de ces données numériques.

Le cours a pour objectif principal de donner des bases de programmation. Mais ce faisant, il propose des éléments de réflexion théorique et épistémologiques sur ce que peuvent ces données numériques pour les sciences sociales, ce qu’elles peuvent leur faire. Il nous semble en effet qu’on ne peut dissocier l’analyse des données des conditions de leur production. 

Le cours peut être suivi en intégralité, ou de manière sélective. Chaque chapitre s’appuie toutefois sur des notions qui ont été vues précédemment. Aucune connaissance préalable en informatique n’est nécessaire.

## 0 – L’abondance et ses revers
Ou ce que l’arrivée massive de données numériques fait aux sciences sociales… parfois.

VIDEO1

## 1 – Données numériques et sciences humaines et sociales
Pourquoi, et comment collecter des données numériques pour une recherche en sciences sociales?

VIDEO2

### Références

* É. Ollion, J. Boelaert, « Au-delà des big Data. Les sciences sociales face à l’abondance de données numériques« , in Sociologie, 2015
* M. Sagalnik, Bit by Bit. Social Research in the Digital Era, Princeton University Press, 2017.

## 1 bis – Introduction à R
Ce cours propose une brève introduction, d’abord littéraire, puis appliquée, au logiciel R.

### Scripts
TD1-intro.R

### Références
Il existe des dizaines de tutoriels, ouvrages, et sites qui permettent de se plonger dans R. Parmi ceux-ci, on peut chaudement recommander :

* Pour une brève introduction, voir ce document réalisé par Julien Barnier, de l’ENS-Lyon.
* Pour plus de détails, voir le projet collaboratif analyse-R.

### Ressources supplémentaires
* Le site de R : [https://cran.r-project.org/](https://cran.r-project.org/)
* La page de téléchargement de Rstudio : [https://www.rstudio.com/products/rstudio/download/](https://www.rstudio.com/products/rstudio/download/)

## 2 – Écrire, et surtout lire le web
À travers une plongée dans l’histoire d’internet et du web, ce cours propose une première approche d’aspects plus techniques comme les langages à balise et les protocoles http, éléments essentiels pour collecter des données en ligne.

### Scripts
* TD2-telechargement-enonce.R
* TD2-telechargement-correction.R

### Sites des exercices

* [https://css.cnrs.fr/scrape/perdue](https://css.cnrs.fr/scrape/perdue)
* [https://css.cnrs.fr/scrape/nobel_news.html](https://css.cnrs.fr/scrape/nobel_news.html)
* [https://css.cnrs.fr/scrape/reperdue](https://css.cnrs.fr/scrape/reperdue)

### Références
* Janet Abate, Inventing the Internet, The MIT Press, 1999.
* Dominique Cardon, Cultures numériques, Presses de Sciences Po, 2019.

## 3 – Sélectionner des données avec XPath
Ce cours propose une introduction au langage Xpath, qui permet de faire des requêtes dans un langage structuré, et ainsi de ne sélectionner que les éléments pertinents.

### Scripts
* TD3-xpath-enonce.R
* TD3-xpath-correction.R

### Sites des exercices

* [https://css.cnrs.fr/scrape/nobel_news.html](https://css.cnrs.fr/scrape/nobel_news.html)
* [https://www.css.cnrs.fr/scrape/nobel_accueil.html](https://css.cnrs.fr/scrape/nobel_news.html)
* [https://www.css.cnrs.fr/scrape/nobel_all.html](https://css.cnrs.fr/scrape/nobel_news.html)

### Ressources supplémentaires
* le site de l’extension chropath pour firefox
* une antisèche utile (en anglais) : https://blog.kvadrati.com/2020/02/xpath-cheatsheet/
* une autre, plus analytique : https://cheatsheetmaker.com/xpath
* un tutoriel ludique pour apprendre les sélecteurs CSS : https://flukeout.github.io/

## 4 – Expressions régulières : recherche avancée et nettoyage de données
Ce cours est une introduction aux expressions régulières (ou regular expressions, Regex en anglais).

### Scripts
* TD4-regex-enonce.R
* TD4-regex-correction.R

### Sites utilisés

* [https://css.cnrs.fr/scrape/lemonde](https://css.cnrs.fr/scrape/lemonde)
* [https://www.css.cnrs.fr/scrape/nobel_all.html](https://www.css.cnrs.fr/scrape/nobel_all.html)

### Références

* Une explication par A. Hobeika
* Des pistes pour aller plus loin sur analyse-r
* Ressources supplémentaires
* Pour tester vos regex : [https://regex101.com/](https://regex101.com/)
* Des mots croisés regex : [https://regexcrossword.com/challenges/beginner/puzzles/1](https://regexcrossword.com/challenges/beginner/puzzles/1)
* Une antisèche de regex : [https://cheatography.com/davechild/cheat-sheets/regular-expressions/](https://cheatography.com/davechild/cheat-sheets/regular-expressions/)

## 5 – Automatiser la collecte
Une fois la collecte des données réalisée sur une page, il faut passer à l’échelle. Ce cours propose une série de conseils pour automatiser le moissonnage.

### Scripts
* TD5-automatisation-enonce.R
* TD5-automatisation-correction.R

### Sites utilisés

* [https://css.cnrs.fr/scrape/multiplication-1.html](https://css.cnrs.fr/scrape/multiplication-1.html)
* [https://css.cnrs.fr/scrape/multiplication-2.html](https://css.cnrs.fr/scrape/multiplication-2.html)
* [https://css.cnrs.fr/scrape/multiplication-10.html](https://css.cnrs.fr/scrape/multiplication-10.html)
* [https://www.css.cnrs.fr/scrape/nobel_accueil.html](https://www.css.cnrs.fr/scrape/nobel_accueil.html)
* [https://www.css.cnrs.fr/scrape/nobel_1900_1920.html](https://www.css.cnrs.fr/scrape/nobel_1900_1920.html)

## 6 – Téléchargement avancé
Comme toutes les pages web ne sont pas forcément accessibles à partir des outils simples présentés en leçon 2, il faut parfois ruser pour réussir à télécharger les pages qui nous intéressent. Cette leçon présente le téléchargement avec des outils presse-bouton comme DownloadThemAll, et le pilotage de navigateur depuis R avec RSelenium.


### Scripts
* TD6-telechargement-correction.R

### Sites utilisés

* [https://css.cnrs.fr/scrape/multiscroll.html](https://css.cnrs.fr/scrape/multiscroll.html)
* [https://css.cnrs.fr/scrape/login.html](https://css.cnrs.fr/scrape/login.html)

### Ressources supplémentaires

* Le site de l’extension Download Them All : [https://www.downthemall.org/](https://www.downthemall.org/)
* La page de téléchargement de Docker : [https://docs.docker.com/engine/install/](https://docs.docker.com/engine/install/)
* Le site du package scraEP : [https://cran.r-project.org/package=scraEP](https://cran.r-project.org/package=scraEP)

## 7- Exercices supplémentaires
Vous trouverez ici quelques exemples supplémentaires de sites pour vous entraîner, ainsi que des démonstrations de méthodes alternatives à celles utilisées dans le cours.

### Scripts
* Exercices supplémentaires: SNSS-exo-supp.R
* Démonstrations rvest, CSS, XML, JSON : SNSS-demo-supp.R

### Sites d’exemples 

* [https://css.cnrs.fr/scrape/lemonde](https://css.cnrs.fr/scrape/lemonde)
* [https://css.cnrs.fr/scrape/europresse](https://css.cnrs.fr/scrape/europresse)
* [https://css.cnrs.fr/scrape/boncoin-page1](https://css.cnrs.fr/scrape/boncoin-page1)
* [https://css.cnrs.fr/scrape/boncoin-page2](https://css.cnrs.fr/scrape/boncoin-page2)
* [https://css.cnrs.fr/scrape/boncoin-page3](https://css.cnrs.fr/scrape/boncoin-page3)
* [https://css.cnrs.fr/scrape/tour_de_france.xml](https://css.cnrs.fr/scrape/tour_de_france.xml)
* [https://css.cnrs.fr/scrape/tour_de_france.json](https://css.cnrs.fr/scrape/tour_de_france.json)

## 8- Crédits
Le cours a été conçu par Julien Boelaert et Étienne Ollion. Le site web a été réalisé par Jan Sodoge.