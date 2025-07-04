---
slug: gene-homology
title: How to find homologous genes in the Entity viewer
description: A table of the homologous genes found in other species for an individual gene of interest.
related_articles:
  - href: ../../../ensembl-data/comparative-genomics/homology-annotation.md
---

# How to find homologous genes in the Entity viewer

Homologous genes share a common ancestor, being separated 'split' by a speciation event or a gene duplication event.

A list of homologous genes for a given gene are found in the homology table.

The homology table for a gene is the first tab in the gene relationship panel found in the detailed view of a gene in the Entity viewer.

<figure>
  <img src="media/gene-homology.png" />
  <figcaption>
    A view of the homology table for BRCA2 in the Entity viewer.
  </figcaption>
</figure>

For each homologous gene found in another species genome the following information is provided:

* __Common name__: Domestic guinea pig
* __Scientific name__: _Cavia porcellus_
* __% Protein similarity__: The percentage of identical amino acid residues aligned against each other.
* __% Coverage__: The percent of query which is in local alignment with the respective reference.
* __Gene symbol__: Gene symbol for homologues in each species - these may vary between species .
* __Gene ID__: the Ensembl ID - ENSG eg ENSCPOG00000005153.4.
* __Hit type__: The type of homology: RBBH: reciprocal best blast hit, BBH: best blast hit.
* __Assembly__: Genome assembly.

### Customising the table

You can reorder the table by sorting on a specific column. To sort the content of a column click on the arrow next to the column heading.

Sorting a specific column will in turn reorganise the information in all other columns of the table.

You can also customise the table by hiding unwanted rows and columns by selecting the appropriate option in the Actions dropdown at the top left of the homology table.

You can download both a customised or uncustomised version of the table selecting the download option in the Actions dropdown.