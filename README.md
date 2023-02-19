# T/BCR-seq-analysis
T/B cell receptor sequencing analysis notes

Please check [awesome vdj](https://github.com/slowkow/awesome-vdj) too!

### tutorials

* [A clonotype nomenclature for T cell receptors](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC2706371/)
* [biostar post on integration scTCR with Seurat](https://www.biostars.org/p/384640/)
* https://repseq-tutorial.readthedocs.io/en/latest/prerequisites.html
* [Welcome to the Immcantation Portal](https://immcantation.readthedocs.io/en/stable/) Use the docker version of Immcantation if you have installation problems. 10x scBCR tutorial using Immcantation https://immcantation.readthedocs.io/en/stable/tutorials/10x_tutorial.html
* [scirpy "getting started" tutorial](https://icbi-lab.github.io/scirpy/tutorials/tutorial_3k_tcr.html) and [case study](https://icbi-lab.github.io/scirpy-paper/wu2020.html) reanalysing 140k T-cells from [Wu et al. (2020)](https://www.nature.com/articles/s41586-020-2056-8). 

### papers

* [Can we predict T cell specificity with digital biology and machine learning?](https://www.nature.com/articles/s41577-023-00835-3)
* [Rep-Seq: uncovering the immunological repertoire through next-generation sequencing](https://www.ncbi.nlm.nih.gov/pubmed/22043864)
* [Single Cell T Cell Receptor Sequencing: Techniques and Future Challenges](https://www.frontiersin.org/articles/10.3389/fimmu.2018.01638/full)
* [T-cell repertoire analysis and metrics of diversity and clonality](https://www.sciencedirect.com/science/article/pii/S0958166920301051?via%3Dihub)
* [TCR-Vγδ usage distinguishes protumor from antitumor intestinal γδ T cell subsets](https://www.science.org/doi/abs/10.1126/science.abj8695)
* [De novo prediction of cancer-associated T cell receptors for noninvasive cancer detection](https://www.science.org/doi/abs/10.1126/scitranslmed.aaz3738)
* [TCR-engineered T cell therapy in solid tumors: State of the art and perspectives](https://www.science.org/doi/10.1126/sciadv.adf3700)


### simulation

[Echidna: Integrated simulations of single-cell immune receptor repertoires and transcriptomes](https://academic.oup.com/bioinformaticsadvances/advance-article/doi/10.1093/bioadv/vbac062/6687122?login=false)

### Tools 

"Cool! I would start with [immunarch](https://immunarch.com/index.html), VDJTools, and the new [scRepertoire](https://github.com/ncborcherding/scRepertoire) package" -- Wʏᴀᴛᴛ MᴄDᴏɴɴᴇʟʟ from 10x genomcis

* [dandelion](https://sc-dandelion.readthedocs.io/en/latest/)  python package for analyzing single cell BCR/TCR data from 10x Genomics 5’ solution! 
* [TRUST4](https://www.nature.com/articles/s41592-021-01142-2) developed in Shirley Liu's group. Use it to extract TCR/BCR information from bulk RNAseq or 5' scRNAseq data.
* [Benchmarking computational methods for B-cell receptor reconstruction from single-cell RNA-seq data](https://www.biorxiv.org/content/10.1101/2022.03.24.485600v2.full)
* We are happy to report a dramatic speedup for one of the core computations for adaptive immune receptor repertoire (AIRR) analysis - the discovery and counting of receptors that overlap between repertoires! Check out our [CompAIRR](https://github.com/uio-bmi/compairr). With 10^4 repertoires of 10^5 sequences each, CompAIRR ran in 17 minutes while the fastest existing tool took 10 days, amounting to a ~1000x speedup
* [ClusTCR](https://svalkiers.github.io/clusTCR/): a Python interface for rapid clustering of large sets of CDR3 sequences with unknown antigen specificity
* [GLIPH2](https://www.nature.com/articles/s41587-020-0505-4)
* [GIANA allows computationally-efficient TCR clustering and multi-disease repertoire classification by isometric transformation](https://www.nature.com/articles/s41467-021-25006-7) from Bo Li.
* [tcrdist3](https://github.com/kmayerb/tcrdist3) is a python API-enabled toolkit for analyzing T-cell receptor repertoires
* [TCRex](https://tcrex.biodatamining.be/): a web tool for the prediction of TCR–epitope recognition
* [ImRex](https://github.com/pmoris/ImRex) TCR-epitope recognition prediction using combined sequence input represention for convolutional neural networks.
* [NetTCR - 2.0](https://services.healthtech.dtu.dk/service.php?NetTCR-2.0) Sequence-based prediction of peptide-TCR binding
* [CellaRepertorium](https://github.com/amcdavid/CellaRepertorium)
* [enclone](https://10xgenomics.github.io/enclone/) from 10x. we should give this a try if we want to cluster TCR and BCR clonotypes.
* [migec](https://github.com/mikessh/migec):A RepSeq processing swiss-knife.
* [MiXCR](https://github.com/milaboratory/mixcr) is a universal software for fast and accurate analysis of T- and B- cell receptor repertoire sequencing data.
* [tcR](http://imminfo.github.io/tcr/): an R package for T cell receptor repertoire advanced data analysis

* [ImReP](https://sergheimangul.wordpress.com/imrep/) is a computational method for rapid and accurate profiling of the adaptive immune repertoire from regular RNA-Seq data.
* [Grouping of Lymphocyte Interactions by Paratope Hotspots](https://github.com/immunoengineer/gliph) paper: https://www.nature.com/nature/journal/v547/n7661/full/nature22976.html

* [TcellMatch](https://github.com/theislab/tcellmatch): Predicting T-cell to epitope specificity. cellMatch is a collection of models to predict antigen specificity of **single T cells** based on CDR3 sequences and other single cell modalities, such as RNA counts and surface protein counts
* [scirpy](https://github.com/icbi-lab/scirpy): A scanpy extension for single-cell TCR analysis. 

* [Tessa](https://github.com/jcao89757/tessa) is a Bayesian model to integrate T cell receptor (TCR) sequence profiling with transcriptomes of T cells. Enabled by the recently developed single cell sequencing techniques, which provide both TCR sequences and RNA sequences of each T cell concurrently, Tessa maps the functional landscape of the TCR repertoire, and generates insights into understanding human immune response to diseases. 
* [DeepTCR](https://github.com/sidhomj/DeepTCR) Deep Learning Methods for Parsing T-Cell Receptor Sequencing (TCRSeq) Data
https://twitter.com/John_Will_I_Am/status/1570837756787691527
https://www.science.org/doi/10.1126/sciadv.abq5089

* [Integrating T cell receptor sequences and transcriptional profiles by clonotype neighbor graph analysis (CoNGA)](https://www.nature.com/articles/s41587-021-00989-2)

### machine learning

* [Structure-based prediction of T cell receptor:peptide-MHC interactions](https://www.biorxiv.org/content/10.1101/2022.08.05.503004v1) Preprint from Philip Bradley where he creates a version of AlphaFold to model TCR:peptide-MHC interactions. Benchmark is far from perfect, but the paper shows that deep learning-based structural modelling is a possible strategy to predict TCR specificity. 

* Uni-Fold: an open-source platform for developing protein models beyond AlphaFold. https://github.com/dptech-corp/Uni-Fold

* Equidock: docking protein receptor and ligand https://github.com/octavian-ganea/equidock_public  news https://news.mit.edu/2022/ai-predicts-protein-docking-0201

* [AlphaFill](https://www.nature.com/articles/s41592-022-01685-y): enriching AlphaFold models with ligands and cofactors

* [ATRAP - Accurate T cell Receptor Antigen Pairing through data-driven filtering of sequencing information from single-cells](https://www.biorxiv.org/content/10.1101/2022.08.31.506001v1)

* [gget alphafold: Predict the 3D structure of a protein from its amino acid sequence using @DeepMind ’s AlphaFold v2.0 from a Python or command-line environment in 3 lines of code. Runs on any laptop and requires only ~4 GB of disk space. Simply ‘pip install gget’.](https://twitter.com/NeuroLuebbert/status/1555968042948915200)

* [ColabFold: making protein folding accessible to all](https://www.nature.com/articles/s41592-022-01488-1)

* [We have trained ESMFold to predict full atomic protein structure directly from language model representations of a single sequence. Accuracy is competitive with AlphaFold on most proteins with order of magnitude faster inference. By @MetaAI Protein Team.](https://mobile.twitter.com/alexrives/status/1550148755206414341)

* [DeepMind AlphaFold for antibody discovery: What's the status?](https://www.naturalantibody.com/use-case/deepmind-alphafold-for-antibody-discovery-whats-the-status/)

* [Why AlphaFold won’t revolutionise drug discovery](https://www.chemistryworld.com/opinion/why-alphafold-wont-revolutionise-drug-discovery/4016051.article) We made AlphaFold dream of new protein assemblies, used #ProteinMPNN to bring it back to reality. https://twitter.com/BasileWicky/status/1570564831522213888

* Here, we introduce [OmegaFold](https://www.biorxiv.org/content/10.1101/2022.07.21.500999v1), the first computational method to successfully predict high-resolution protein structure from a single primary sequence alone. Using a new combination of a protein language model that allows us to make predictions from single sequences and a geometry-inspired transformer model trained on protein structures, OmegaFold outperforms RoseTTAFold and achieves similar prediction accuracy to AlphaFold2 on recently released structures.

* [Hallucinating symmetric protein assemblies](https://www.science.org/doi/10.1126/science.add1964)

* [Learning inverse folding from millions of predicted structures](https://www.biorxiv.org/content/10.1101/2022.04.10.487779v1) https://twitter.com/alexrives/status/1513603415959556096

* [PSP: Million-level Protein Sequence Dataset for Protein Structure Prediction}(https://arxiv.org/abs/2206.12240)

* [Fast, accurate ranking of engineered proteins by receptor binding propensity using structural modeling](https://www.biorxiv.org/content/10.1101/2023.01.11.523680v1.full) https://twitter.com/DingXiaozhe/status/1618257727515676672

### database

* The [IPD-IMGT/HLA Database](https://www.ebi.ac.uk/ipd/imgt/hla/) provides a specialist database for sequences of the human major histocompatibility complex (MHC) and includes the official sequences named by the WHO Nomenclature Committee For Factors of the HLA System. The IPD-IMGT/HLA Database is part of the international ImMunoGeneTics project (IMGT). 

* [TCRdb](http://bioinfo.life.hust.edu.cn/TCRdb/#/) A comprehensive database of human T-cell receptor (TCR) sequences
* [Immuno-Navigator](https://genomics.virus.kyoto-u.ac.jp/immuno-navigator/) A database for gene coexpression in the immune system
* [McPAS-TCR](http://friedmanlab.weizmann.ac.il/McPAS-TCR/) A manually curated catalogue of pathology associated T-cell receptor sequences
* [Vdjdb](https://vdjdb.cdr3.net/)
* @OPIGlets has built lots of lovely stuff including SAbPred, OAS, TAP http://opig.stats.ox.ac.uk/resources

