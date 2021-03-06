Analysis of the UNAM's admission exam
======================================

[![Continuous Integration status](https://secure.travis-ci.org/diegovalle/unam.png)](http://travis-ci.org/diegovalle/unam)

The UNAM is by far the most important university in Mexico. Interestingly, the university makes all the results of the students who took the admission exam available at their website. This program analyses those results.

The [web page](https://servicios.dgae.unam.mx/Junio2013/resultados/) where the test results were made public contains the following legalese:

> Hecho en México, todos los derechos reservados 2009. Esta página puede ser reproducida con fines no lucrativos, siempre y cuando no se mutile, se cite la fuente completa y su dirección electrónica. De otra forma requiere permiso previo por escrito de la institución.

The rest of this work is licensed under a [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).

To run you'll need Python 2.7, R 3, and imagemagick. The program was tested on Ubuntu

```
make
```

Since the UNAM has the bad habit of erasing old pages the repository includes a cache of all the admission result pages in the cache directory. There's also a copy of the database containing all the data from June 2011 to Feb. 2014 (note that the analysis is only up to June 2013, since the scrapper still worked, I added the Feb. 2014 data) 

```
clean-data\unam-admission.csv
```
