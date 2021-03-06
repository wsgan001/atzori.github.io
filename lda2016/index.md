---
layout: bootstrap
title: Publishing Linked Data - Methodologies and Tools
---




Publishing Linked Data: Methodologies and Tools (LDA 2016)
========
This page contains teaching material (slides and links) related to my course *Publishing Linked Data: Methodologies and Tools* (PUBBLICARE LINKED DATA
Metodologie e strumenti) which is part of the Summer School [Libraries in the Digital Age (LDA) 2016](http://lda2016.unica.it/).

Slides
------
Slides are available [here](http://atzori.webofcode.org/lda2016/lda2016-atzori.pdf).

Videos
------
 - [Introduction to Linked Data](https://vimeo.com/36752317) 
 - [From Excel file to RDF with links to DBpedia and Europeana (using OpenRefine)](https://youtu.be/XdpzmGxA33U)
 - [Another example of using OpenRefine to produce RDF triples from tabular data](https://youtu.be/B5CsSE7_zeQ)
 - [Tim Berners-Lee, publicizing LOD for TIM](https://youtu.be/-rxy9lI8-7Q)
 - [Tim Berners-Lee's talk at TED in 2009](https://youtu.be/OM6XIICm_qo)

Book
----
[Linked Data: Evolving the Web into a Global Data Space](http://linkeddatabook.com/editions/1.0/) by  Tom Heath (Talis) and Christian Bizer (Freie Universität Berlin)

Links
-----
 - [LODrefine](https://sourceforge.net/projects/lodrefine/), an RDF-featured version of *OpenRefine* (formerly Google Refine)
 - [this page](http://atzori.webofcode.org/lda2016/)
 - [Summer School LDA 2016](http://lda2016.unica.it/)
 - [http://www.orestesignore.eu/education/lda/](http://www.orestesignore.eu/education/lda/)
 - [Introduzione al Semantic Web by Oreste Signore](http://www.w3c.it/papers/wsb08.pdf)

LodRefine Settings
------
In order to reconcile properly against DBpedia, create a reconciliation service using the following settings:

  - matchThreshold: 0.9
  - searchPropertyUris: "http://www.w3.org/2000/01/rdf-schema#label", "http://dbpedia.org/property/name"
  - type: Virtuoso,
  - endpoint: "http://dbpedia.org/sparql"
 
