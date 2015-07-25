# ol3-zoom-to

An Openlayers 3 module for 'zooming' to a particular location on the map based on input via Decimal Degrees, Degrees Minutes Seconds, or Military Grid Reference System.

[DEMO](http://plnkr.co/edit/eacYfgt7ysNNV4htOpCA?p=preview)

---

##### Dependencies: #####
1. Openlayer3: http://openlayers.org/download/
2. The mgrs.js library for parsing mgrs coordinates: https://github.com/proj4js/mgrs
3. The feedback mechanism for errors uses toastr.js: https://github.com/CodeSeven/toastr

---
#####Test coordinates in various formats:#####

12356N 1234567E

12356.00N 1234567.00E

12°34'56N 123°45'67E

12°34'56.00 N 123°45'67.00 E

12°34'56.00N 3°45'67.00E

12 34 56N 123 45 67E

12:34:56 N 123:45:67 E

12:34:56.00N 123:45:67.00E

34°36'57.0"S 58°25'60.0"W (Buenos Aires)

35°32'20.2"N 82°33'55.5"W (Asheville, NC)

18S UJ 23480 06470 (Washington D.C.)
