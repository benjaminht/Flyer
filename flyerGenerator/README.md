Python-script f�r Netz39 e.V. Flyer und Poster
===============================================

* liest den ical-feed von netz39.de/events
* bef�llt ein jinja2 template, basierend auf ../LatexTemplate
* generiert .pdfs f�r Flyer und Poster
* verschiebt pdfs in 'out'-Ordner
* l�scht .aux, .log etc.

Standardwerte:
* ab 1. des aktuellen Monats
* f�r die n�chsten 2 Monate