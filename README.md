OCDS Indonesia
==============

A data repository for Indonesia procurement data using [OCDS specification](http://ocds.open-contracting.org/standard/r/0__3__3/).

The mapping technique is based on [open-contracting/mapper](https://github.com/open-contracting/mapper) project developed by Sarah Bird. Please find the detail instructions [here](http://standard.open-contracting.org/field-notes-transforming-canadian-procurement-data-to-ocds-format/).

Below is the example for running the mapping script:
```
$ cd oc-mapper
$ python mapper.py --csv-file ../lpse-procurement-2013.csv --mapping-file ../mapping-lpse-procurement.json > ../lpse-procurement-2013.json
```

Licensing
---------

This repository contains all public data sets published by the Open Data Lab Jakarta. In general, the lab uses Open Data Commons Open Database 1.0 License (ODC-ODbL) that allows you to share, create and adapt the offered databases.
However, you are obligated to attribute, share-alike and keep the redistribution open.

Read [full-text](http://opendatacommons.org/licenses/odbl/1.0/).
