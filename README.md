# quantumchem
searching Open Access literature for quantum chemistry (inspiration Leonie Mueck)

## miniproject at eLife Sprint Cambridge 2019
petermr is offering miniproject/s in searching the Open Access Literature on any subjects in EuropePMC or possibly beyond.

Leonie Mueck suggested "quantum chemistry", this is a prototype.

## communal resources for OpenNotebook
Much of the code and processes are shared between the OpenNotebook projects, see:
[OpenNotebook](https://github.com/petermr/openNotebook/blob/master/README.md)


## issues
Github issues used to manage the project.
### dictionaries

## dictionaries
We need dictionaries for key concepts/ terms. Suggest:
### basis-sets
### functionals
### software

## corpora
Initial corpus of 100 EPMC papers:
```
getpapers -x -o qchem -q "quantum chemistry" -k 100
```

## initial dataTable scoping
```
 ami-search -p qchem/ --dictionary country funders
```
 

