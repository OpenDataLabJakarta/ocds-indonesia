OCDS Indonesia
==============

A data repository for Indonesia procurement data using [OCDS specification](http://ocds.open-contracting.org/standard/r/0__3__3/).

The mapping technique is based on [open-contracting/mapper](https://github.com/open-contracting/mapper) project developed by Sarah Bird. Please find the detail instructions [here](http://standard.open-contracting.org/field-notes-transforming-canadian-procurement-data-to-ocds-format/).

Below is the example for running the mapping script:
```
$ python oc-mapper/mapper.py 
    --csv-file lpse-procurement-2013.csv
    --mapping-file mapping-lpse-procurement.json 
    --ocid-prefix ocds --ocid-namespace odlab > lpse-procurement-2013.json
```

Licensing
---------

This repository contains public datasets published by the Open Data Lab Jakarta under [Open Data Commons Open Database 1.0 License (ODC-ODbL)](http://opendatacommons.org/licenses/odbl/1.0/).

```
You are free:
- To Share: To copy, distribute and use the database.
- To Create: To produce works from the database.
- To Adapt: To modify, transform and build upon the database.

As long as you:
- Attribute: You must attribute any public use of the database, or works produced
from the database, in the manner specified in the ODbL. For any use or redistribution
of the database, or works produced from it, you must make clear to others the license
of the database and keep intact any notices on the original database.
- Share-Alike: If you publicly use any adapted version of this database, or works
produced from an adapted database, you must also offer that adapted database under
the ODbL.
- Keep open: If you redistribute the database, or an adapted version of it, then you
may use technological measures that restrict the work (such as DRM) as long as you
also redistribute a version without such measures.
```
