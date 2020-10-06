# T/BCR-seq-analysis
T/B cell receptor sequencing analysis notes

### tutorials

* [A clonotype nomenclature for T cell receptors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2706371/)
* [biostar post on integration scTCR with Seurat](https://www.biostars.org/p/384640/)
* https://repseq-tutorial.readthedocs.io/en/latest/prerequisites.html
* [Welcome to the Immcantation Portal](https://immcantation.readthedocs.io/en/stable/) Use the docker version of Immcantation. installation is very hard. 10x scBCR tutorial using Immcantation https://immcantation.readthedocs.io/en/stable/tutorials/10x_tutorial.html
* [scirpy "getting started" tutorial](https://icbi-lab.github.io/scirpy/tutorials/tutorial_3k_tcr.html) and [case study](https://icbi-lab.github.io/scirpy-paper/wu2020.html) reanalysing 140k T-cells from [Wu et al. (2020)](https://www.nature.com/articles/s41586-020-2056-8). 

### papers

* [Rep-Seq: uncovering the immunological repertoire through next-generation sequencing](https://www.ncbi.nlm.nih.gov/pubmed/22043864)
* [Single Cell T Cell Receptor Sequencing: Techniques and Future Challenges](https://www.frontiersin.org/articles/10.3389/fimmu.2018.01638/full)
### Tools 

"Cool! I would start with [immunarch](https://immunarch.com/index.html), VDJTools, and the new [scRepertoire](https://github.com/ncborcherding/scRepertoire) package" -- Wʏᴀᴛᴛ MᴄDᴏɴɴᴇʟʟ from 10x genomcis

* [CellaRepertorium](https://github.com/amcdavid/CellaRepertorium)
* [migec](https://github.com/mikessh/migec):A RepSeq processing swiss-knife.
* [MiXCR](https://github.com/milaboratory/mixcr) is a universal software for fast and accurate analysis of T- and B- cell receptor repertoire sequencing data.
* [tcR](http://imminfo.github.io/tcr/): an R package for T cell receptor repertoire advanced data analysis

* [ImReP](https://sergheimangul.wordpress.com/imrep/) is a computational method for rapid and accurate profiling of the adaptive immune repertoire from regular RNA-Seq data.
* [Grouping of Lymphocyte Interactions by Paratope Hotspots](https://github.com/immunoengineer/gliph) paper: https://www.nature.com/nature/journal/v547/n7661/full/nature22976.html

* [TcellMatch](https://github.com/theislab/tcellmatch): Predicting T-cell to epitope specificity. cellMatch is a collection of models to predict antigen specificity of **single T cells** based on CDR3 sequences and other single cell modalities, such as RNA counts and surface protein counts
* [scirpy](https://github.com/icbi-lab/scirpy): A scanpy extension for single-cell TCR analysis. 

### database

* The [IPD-IMGT/HLA Database](https://www.ebi.ac.uk/ipd/imgt/hla/) provides a specialist database for sequences of the human major histocompatibility complex (MHC) and includes the official sequences named by the WHO Nomenclature Committee For Factors of the HLA System. The IPD-IMGT/HLA Database is part of the international ImMunoGeneTics project (IMGT). 

* [TCRdb](http://bioinfo.life.hust.edu.cn/TCRdb/#/) A comprehensive database of human T-cell receptor (TCR) sequences
* [Immuno-Navigator](https://genomics.virus.kyoto-u.ac.jp/immuno-navigator/) A database for gene coexpression in the immune system
