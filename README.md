# MODEL1106160000: iAS253

## Installation

Download this repository, and install with distutils

`python setup.py install`

Or, install using pip

`pip install git+https://github.com/biomodels/MODEL1106160000.git`

To install a specific version (in this example, from the 2014-09-16 BioModels release)

`pip install git+https://github.com/biomodels/MODEL1106160000.git@20140916`

## Usage

Importing the model package.

`import MODEL1106160000 as model`

Get the SBML string from the model

`print model.sbmlString`

If [python-libsbml](https://pypi.python.org/pypi/python-libsbml) bindings are
installed, the libsbml.SBMLDocument object is also accessible

`model.sbml`


# Model Notes


This model is from the article:  
**A metabolic model of the mitochondrion and its use in modelling diseases of the tricarboxylic acid cycle.**   
Smith AC, Robinson AJ. _BMC Syst Biol._ 2011 Jun 29;5(1):102.
[21714867](http://www.ncbi.nlm.nih.gov/pubmed/21714867) ,  
**Abstract:**   
BACKGROUND:Mitochondria are a vital component of eukaryotic cells and their
dysfunction is implicated in a large number of metabolic, degenerative and
age-related human diseases. The mechanism or these disorders can be difficult
to elucidate due to the inherent complexity of mitochondrial metabolism. To
understand how mitochondrial metabolic dysfunction contributes to these
diseases, a metabolic model of a human heart mitochondrion was created.
RESULTS: A new model of mitochondrial metabolism was built on the principle of
metabolite availability using MitoMiner, a mitochondrial proteomics database,
to evaluate the subcellular localisation of reactions that have evidence for
mitochondrial localisation. Extensive curation and manual refinement was used
to create a model called iAS253, containing 253 reactions, 245 metabolites and
89 transport steps across the inner mitochondrial membrane. To demonstrate the
predictive abilities of the model, flux balance analysis was used to calculate
metabolite fluxes under normal conditions and to simulate three metabolic
disorders that affect the TCA cycle: fumarase deficiency, succinate
dehydrogenase deficiency and alpha-ketoglutarate dehydrogenase deficiency.
CONCLUSION: The results of simulations using the new model corresponded
closely with phenotypic data under normal conditions and provided insight into
the complicated and unintuitive phenotypes of the three disorders, including
the effect of interventions that may be of therapeutic benefit, such as low
glucose diets or amino acid supplements. The model offers the ability to
investigate other mitochondrial disorders and can provide the framework for
the integration of experimental data in future studies.

Created by Anthony C. Smith (Mon Mar 14 11:03:11 2011) MRC - Mitochondrial
Biology Unit, Cambridge, UK. acs@mrc-mbu.cam.ac.uk

This metabolic network is a stocihiometric model of a human heart
mitochondrion. Identifiers are KEGG Ids.

This model originates from BioModels Database: A Database of Annotated
Published Models (http://www.ebi.ac.uk/biomodels/). It is copyright (c)
2005-2011 The BioModels.net Team.  
To the extent possible under law, all copyright and related or neighbouring
rights to this encoded model have been dedicated to the public domain
worldwide. Please refer to [CC0 Public Domain
Dedication](http://creativecommons.org/publicdomain/zero/1.0/) for more
information.

In summary, you are entitled to use this encoded model in absolutely any
manner you deem suitable, verbatim, or with modification, alone or embedded it
in a larger context, redistribute it, commercially or not, in a restricted way
or not..  
  
To cite BioModels Database, please use: [Li C, Donizelli M, Rodriguez N,
Dharuri H, Endler L, Chelliah V, Li L, He E, Henry A, Stefan MI, Snoep JL,
Hucka M, Le Novère N, Laibe C (2010) BioModels Database: An enhanced, curated
and annotated resource for published quantitative kinetic models. BMC Syst
Biol., 4:92.](http://www.ncbi.nlm.nih.gov/pubmed/20587024)


