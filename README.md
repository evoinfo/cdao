# Comparative Data Analysis Ontology - CDAO

CDAO is an ontology for use in the evolutionary analysis of biological data.  The ontology is represented in OWL-DL (Web Ontology Language with Description Logics).

CDAO includes concepts that represent phylogenetic trees, as well as the character-state data model.  The character-state data model is an entity-attribute-value model in which the entities are biological entities such as genes, proteins, or species, typically referred to as OTUs (Operational Taxonomic Units), the attributes are called "Characters", and the value of an attribute for a given entity is called the "State" or "Character state", e.g., in a protein alignment, the proteins are the entities, the alignment columns are the attributes, and the values are the residues specified by row and column.

## History

CDAO was originally developed by the [Evolutionary Informatics working group] of the National Evolutionary Synthesis Center ([NESCent]).  The original developers included Brandon Chisham, Francisco Prosdocimi, Julie Thompson, Enrico Pontelli, and Arlin Stoltzfus.

In 2012 Jim Balhoff (affiliated at the time with NESCent and the [Phenoscape] project) took over maintenance of the ontology and migrated it to OBO naming, identifier, and IRI conventions.

For continued development, the ontology and all project history were migrated in 2017 from the [CVS and Subversion repositories at SourceForge][sf.net project] to a Git repository hosted at Github.

## Citation 

Please cite the following publication if you use CDAO in your work.

> Prosdocimi F, Chisham B, Pontelli E, Thompson J, Stoltzfus A. [Initial Implementation of a comparative Data Analysis Ontology][Prosdocimi et al 2009]. Evol Bioinform Online. 2009; 47–66.

The ontology itself is available under the [CC Zero] public domain waiver.

[Evolutionary Informatics working group]: https://evoinfo.nescent.org
[NESCent]: http://nescent.org
[Phenoscape]: http://phenoscape.org
[sf.net project]: https://sf.net/p/cdao
[Prosdocimi et al 2009]: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2747124/
[CC Zero]: http://creativecommons.org/publicdomain/zero/1.0/
