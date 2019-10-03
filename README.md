# Quantumchem
Searching Open Access literature for quantum chemistry (inspiration Leonie Mueck)

## Miniproject at eLife Sprint Cambridge 2019
Petermr is offering miniproject/s in searching the Open Access Literature on any subjects in EuropePMC or possibly beyond.

Leonie Mueck suggested "quantum chemistry", this is a prototype.

## Communal resources for OpenNotebook
Much of the code and processes are shared between the OpenNotebook projects, see:
[OpenNotebook](https://github.com/petermr/openNotebook/blob/master/README.md)


## Issues
Github issues used to manage the project.
### Dictionaries

## Dictionaries
We need dictionaries for key concepts/ terms. Suggest:
### Basis-sets
### Functionals
### Software

## Corpora
Initial corpus of 100 EPMC papers:
```
getpapers -x -o qchem -q "quantum chemistry" -k 100
```

## Initial dataTable scoping
```
 ami-search -p qchem/ --dictionary country funders
```
 

