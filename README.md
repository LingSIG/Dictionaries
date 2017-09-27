# TEI Lex0: Dictionary samples

The "Dictionaries" project of TEI LingSIG is a spin-off of the joint ENeL/PARTHENOS/DARIAH project "TEI Lex0". It features two repositories:
* LingSIG/Dictionaries (this one) for storing (i) samples of dictionaries, (ii) stylesheets for conversion between the outer world and Lex0, and (iii) ODD for TEI-Lex0
* [LingSIG/TEI (branch: dictionaries)](https://github.com/LingSIG/TEI/tree/dictionaries) for suggested changes in the Guidelines documentation (treat it as being there "just in case" for now; things may come up that require some pull requests against the Guidelines, but just as well it may happen that feature requests or bug reports at TEI-C will be enough)

## Contents
### samples/
This directory collects samples of dictionary entries. For digitised dictionaries, please consider attaching a scan of the entry in the printed version.

### tools/
This directory holds tools for the transformation to/from Lex0, vis-à-vis the samples/ directory

### ODD/
Stores the combined ODD for TEI Lex0.
As of September 2017 (or so), you may expect the ODD to specify documentation for elements of `<form>` and `<gramGrp>`, as discussed in ["TEI-Lex0 Guidelines for the Encoding of Dictionary Information on Written and Spoken Forms"](https://elex.link/elex2017/wp-content/uploads/2017/09/paper29.pdf) by Piotr Bański, Jack Bowers and Tomaž Erjavec (paper given at [eLex 2017](https://elex.link/elex2017/).

### Lex0.rng
RELAX NG schema file with embedded Schematron rules, based on the ODD.

### Lex0-demo.xml
This is a test file to try out the ODD (via the schema generated from it).

## Licensing
Unless stated explicitly to the contrary, material deposited here is assumed to match the licensing conditions of the TEI Guidelines, namely [CC+BY 3.0 Unported and BSD 2-clause](http://www.tei-c.org/Guidelines/access.xml).
