# PhytoREF - A reference database of the plastidial 16S rRNA gene of photosynthetic eukaryotes with curated taxonomy
[![Release](https://img.shields.io/badge/release-1.0-blue.svg)
![Date](https://img.shields.io/badge/date-01%20July%202020-lightgrey.svg)
![Github Downloads
(total)](https://img.shields.io/github/downloads/roskobaz/phytoref/total.svg)](https://github.com/roskobaz/cyanomarks/releases)

## Welcome to the PhytoREF database!
Photosynthetic eukaryotes have a critical role as the main producers in most ecosystems of the biosphere. Environmental metabarcoding is a powerful approach to assess the composition and global distribution of algal communities, in particular the unicellular microalgae that often lack distinctive morphological characters. However, metabarcoding necessarily relies on taxonomically curated databases containing reference sequences of the targeted gene (or barcode) from identified organisms.

The PhytoREF database provides an access to plastidial 16S rRNA gene sequences of a large diversity of photosynthetic eukaryotes with curated and normalized taxonomy. PhytoREF has been built using the publicly available sequences and plastidial genomes from GenBank, as well as, new amplicon sequences obtained from numerous cultures of marine phytoplankton. Stringent quality filtering and phylogeny-based taxonomic classification were applied for each single 16S rRNA gene sequence. All the major eukaryotic lineages that perform photosynthesis or keep a relict plastid are represented in PhytoREF, and comprise terrestrial, freshwater and marine taxa (land plants, marine and freshwater macro and microalgae).

PhytoREF is not only a new tool to explore, evaluate and monitor the diversity of photosynthetic eukaryotes in different ecosystems with metabarcoding approaches, but also a genomic resource to annotate new 16S rRNA sequences, and design primers and probes. This new database can be used for many purposes from biomonitoring of photosynthetic eukaryotes in various habitats (e.g. water, sediment, ice), paleoecological studies in past environments, to dietary studies. 

## What we provide
We provide 6010 16S rDNA sequences.

Numerous supporting data are also provided including:
* deep phylogenetic classification down to the subclade level, unified between markers,
* physiological information (e.g. pigment type),
* contextual data (e.g. isolation site, GPS coordinates, physico-chemical parameters),
* literature citations, year of isolation and publication

## Current version
* Current version : 1.0
* Last update : 1st of July, 2020 
* DOI
* [Link](https://github.com/roskobaz/phytoref/releases)
* Documentation

## Curators
* [Johan Decelle](mailto:johan.decelle@univ-grenoble-alpes.fr), CNRS-Sorbonne Université · Station Biologique, 29680 Roscoff FRANCE
* n'Co

## How to Cite
Decelle, J., Romac, S., Stern, R. F., Bendif, E. M., Zingone, A., Audic, S., Guiry, M. D., Guillou, L., Tessier, D., Le Gall, F., Gourvil, P., Dos Santos, A. L., Probert, I., Vaulot, D., de Vargas, C. and Christen, R. (2015), **PhytoREF: a reference database of the plastidial 16S rRNA gene of photosynthetic eukaryotes with curated taxonomy.** [Mol Ecol Resour, 15: 1435-1445](http://onlinelibrary.wiley.com/doi/10.1111/1755-0998.12401/abstract). [doi:10.1111/1755-0998.12401](https://onlinelibrary.wiley.com/doi/abs/10.1111/1755-0998.12401)

## Provided Files

|File suffix             |File Content                                                                          |
|------------------------|--------------------------------------------------------------------------------------|
|contextual_data.csv.gz  |A tabulated file containing all contextual data, including environmental parameters.  |
|dada2.fasta.gz          |A fasta of all reference sequences with DADA2-formatted headers                       |
|mothur.fasta.gz         |A fasta of all reference sequences with MOTHUR-formatted headers                      |
|mothur.tax.gz           |A text file of taxonomies for MOTHUR                                                  |
|taxo_long.fasta.gz      |A fasta of all reference sequences with long "n-ranked" taxonomy                      |
|UTAX.fasta.gz           |A fasta of all reference sequences with VSEARCH-formatted headers                     |


## Report issues
* Please report any issue on [GitHub](https://github.com/roskobaz/cyanomarks/issues)
