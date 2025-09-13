# SFKs MSA Pipeline
This repository contains a set of scripts I developed during my undergraduate research to study the evolutionary conservation of Src family kinases (SFKs) across diverse species. The pipeline automates database preparation, sequence retrieval, homology search, multiple sequence alignment, and visualization.

## BLAST database generation
- Automated creation of protein BLAST databases from multiple species proteomes.
- Implemented in Bash and AWK using makeblastdb

## Sequence retrieval and homology search
- Download of query protein sequences from [UniProt](https://www.uniprot.org/).
- Batch BLASTp searches across species.

## Multi-sequence alignment
- Alignment of homologous sequences using ClustalW.
- MSA visualization with [pyMSAviz](https://github.com/moshi4/pyMSAviz).
- Customizable annotation

## Requirements
- **NCBI BLAST**
- **ClustalW**
- **Python 3**
- Bash, AWK
