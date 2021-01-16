# GeoPose User Guide README

## Content

This folder contains all files for the GeoPose User Guide

* GeoPose-Users-Guide.adoc - the main User Guide document with references to all sections
* remaining adocs - each section of the Best Practice document is in a separate document: follow directions in each document to populate
* figures - figures used in the GeoPose-Users-Guide.adoc
* images - images used in the GeoPose-Users-Guide.adoc go here. Image files for figures go in the "figures" directory. Only place in here images not used in figures (e.g., as parts of tables, as logos, etc.)
* code - (OPTIONAL)sample code to accompany the Best Practice, if desired
* abstract_tests - (OPTIONAL)the Abstract Test Suite comprising one test for every requirement, optional
* UML - UML diagrams, if applicable

## Building

To produce the HTML of the Best Practice run `asciidoctor --safe -a data-uri -o
GeoPose-Users-Guide.html GeoPose-Users-Guide.adoc`

To produce the PDF of the Best Practice run `asciidoctor-pdf --safe -o
GeoPose-Users-Guide.html GeoPose-Users-Guide.adoc`
