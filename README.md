# BIOMD0000000526: MODEL1403050003

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/BIOMD0000000526.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/BIOMD0000000526.git@20140916`

## Usage

Importing the model package.

`import BIOMD0000000526 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


Kallenberger2014 - CD95L induced apoptosis initiated by caspase-8, wild-type
HeLa cells (cis/trans-cis/trans variant)

The paper describes a new approach that combines single cell and population
data in the same model. The model consists of a large number of single cell
models, which are fitted to single cell data. Simultaneously, ensemble
averages are fitted to population data. It is assumed that the kinetics in
each cell can be described with the same kinetic parameters. Therefore, cell-
to-cell variability is explained by variable initial protein concentrations.

There are four variants of the model (with [CD95L]=500ng/ml = 16.6nM), i)
cistrans (in CD95-HeLa cells) [
[MODEL1403050000](http://identifiers.org/biomodels.db/MODEL1403050000) ], ii)
cistrans (in wild-type HeLa cells) [
[MODEL1403050001](http://identifiers.org/biomodels.db/MODEL1403050001) ], iii)
cistrans-cistrans (in CD95-HeLa cells) [
[MODEL1403050002](http://identifiers.org/biomodels.db/MODEL1403050002) ], and
iv) cistrans-cistrans (in wild-type HeLa cells) [
[MODEL1403050003](http://identifiers.org/biomodels.db/MODEL1403050003) ].

These model contain the equations for one "average cell" with median initial
concentrations for CD95, FADD, p55, BID, PrNES_mCherry and PrER_mGFP. By
integrating the model, it should be possible to obtain trajectories for
PrER_mGFP, PrNES_mCherry, p43 and p18 similar as in Figure 4A (CD95-HeLa
cells) and Figure 4B (wild-type HeLa cells).

This model is described in the article:

[Intra- and Interdimeric Caspase-8 Self-Cleavage Controls Strength and Timing
of CD95-Induced
Apoptosis](http://identifiers.org/doi/10.1126/scisignal.2004738)

Stefan M. Kallenberger, Joël Beaudouin, Juliane Claus, Carmen Fischer, Peter
K. Sorger, Stefan Legewie, and Roland Eils

11 March 2014: Vol. 7, Issue 316, p. ra23

Abstract:

Apoptosis in response to the ligand CD95L (also known as Fas ligand) is
initiated by caspase-8, which is activated by dimerization and self-cleavage
at death-inducing signaling complexes (DISCs). Previous work indicated that
the degree of substrate cleavage by caspase-8 determines whether a cell dies
or survives in response to a death stimulus. To determine how a death ligand
stimulus is effectively translated into caspase-8 activity, we assessed this
activity over time in single cells with compartmentalized probes that are
cleaved by caspase-8 and used multiscale modeling to simultaneously describe
single-cell and population data with an ensemble of single-cell models. We
derived and experimentally validated a minimal model in which cleavage of
caspase-8 in the enzymatic domain occurs in an interdimeric manner through
interaction between DISCs, whereas prodomain cleavage sites are cleaved in an
intradimeric manner within DISCs. Modeling indicated that sustained membrane-
bound caspase-8 activity is followed by transient cytosolic activity, which
can be interpreted as a molecular timer mechanism reflected by a limited
lifetime of active caspase-8. The activation of caspase-8 by combined intra-
and interdimeric cleavage ensures weak signaling at low concentrations of
CD95L and strongly accelerated activation at higher ligand concentrations,
thereby contributing to precise control of apoptosis.

This model is hosted on [BioModels Database](http://www.ebi.ac.uk/biomodels/)
and identified by:
[BIOMD0000000526](http://identifiers.org/biomodels.db/BIOMD0000000526) .

To cite BioModels Database, please use: [BioModels Database: An enhanced,
curated and annotated resource for published quantitative kinetic
models](http://identifiers.org/pubmed/20587024) .

To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.


