# CAFPdb
The consensus antifungal peptide database.

## Stages of Analysis

* 00 Data Recolection
* 01 Database Properties
* 02 Similarity Comparison against SwissProt Database
* 03 Clustering and Analysis 

The consensus antifungal peptide database is full with 6,196 unique sequences.

## 00 Data Recolection and clean from the Databases

* Folder: 00_CAFPdb_fastas

| Database                                                                                    | Peptides Fasta (Totales DB) | AntiFungi From DB | Last Update   | Url                                                                                          | Reference                                                                                                                                                      |
| ------------------------------------------------------------------------------------------- | --------------------------- | ----------------- | ------------- | -------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| AHTPDB: A Comprehensive Platform for Analysis and Presentation of Antihypertensive Peptides | 3281 (5978)                 | NA                | Sep 14, 2020  | [https://webs.iiitd.edu.in/raghava/ahtpdb](https://webs.iiitd.edu.in/raghava/ahtpdb)         | [https://doi.org/10.1093/nar/gku1141](https://doi.org/10.1093/nar/gku1141)                                                                                     |
| APD3: The Antimicrobial Peptide Database                                                    | 3180 (3324)                 | 1230              | *Jan 6, 2022* | [https://aps.unmc.edu](https://aps.unmc.edu/)                                                | [https://doi.org/10.1093/nar/gkv1278](https://doi.org/10.1093/nar/gkv1278.)                                                                                    |
| CAMPR3: A Database on Sequences, Structures and Signatures of Antimicrobial Peptides        | 8164 (10247)                | 1144              | 2019?         | [http://www.camp.bicnirrh.res.in](http://www.camp.bicnirrh.res.in)                           | [https://doi.org/10.1093/nar/gkv1051](https://doi.org/10.1093/nar/gkv1051.) [https://doi.org/10.1002/pro.3714](https://doi.org/10.1002/pro.3714)               |
| CancerPPD: Database of Anticancer Peptides and Proteins                                     | 3491 (3491)                 | NA                | 2015?         | [http://crdd.osdd.net/raghava/cancerppd](http://crdd.osdd.net/raghava/cancerppd/)            | [https://doi.org/10.1093/nar/gku892](https://doi.org/10.1093/nar/gku892.)                                                                                      |
| CPP: Database of Cell Penetrating Peptides                                                  | 1559 (1855)                 | NA                | 2015?         | [https://webs.iiitd.edu.in/raghava/cppsite](https://webs.iiitd.edu.in/raghava/cppsite)       | [https://doi.org/10.1093/nar/gkv1266](https://doi.org/10.1093/nar/gkv1266)                                                                                     |
| DBAASP3: Database of Antimicrobial Activity and Structure of Peptides                       | 15598 (18433)               | 5579              | 2021          | [https://dbaasp.org](https://dbaasp.org)                                                     | [https://doi.org/10.1111/1574-6968.12489](https://doi.org/10.1111/1574-6968.12489), [https://doi.org/10.1093/nar/gkaa991](https://doi.org/10.1093/nar/gkaa991) |
| DbAMP: Antimicrobial peptides (AMPs) Database                                               | 11904(11904)                | NA                | Jun 20, 2019  | [http://140.138.77.240/~dbamp](http://140.138.77.240/~dbamp)                                 | [https://doi.org/10.1093/nar/gky1030](https://doi.org/10.1093/nar/gky1030)                                                                                     |
| DRAMP3: Data repository of antimicrobial peptides Database                                  | 8708(22259)                 | 1802              | Jan 5, 2022   | [http://dramp.cpu-bioinfor.org](http://dramp.cpu-bioinfor.org)                               | [https://doi.org/10.1093/nar/gkab651](https://doi.org/10.1093/nar/gkab651)                                                                                     |
| EROP: Endogenous Regulatory OligoPeptide knowledgebase                                      | 22553(26751)                | 812               | June 29, 2020 | [http://erop.inbi.ras.ru](http://erop.inbi.ras.ru)                                           | [https://doi.org/10.1093/nar/gkj008](https://doi.org/10.1093/nar/gkj008)                                                                                       |
| LAMP2: An update to LAMP database linking antimicrobial peptide.                            | 22532(23253)                | 2147              | 2019          | [http://biotechlab.fudan.edu.cn/database/lamp](http://biotechlab.fudan.edu.cn/database/lamp) | [https://doi.org/10.1371/journal.pone.0066557](https://doi.org/10.1371/journal.pone.0066557)                                                                   |
| PAMP: Database dedicated to these plant AMPs                                                | 273(273)                    | 80                | 2009          | [http://phytamp.pfba-lab-tun.org](http://phytamp.pfba-lab-tun.org)                           | [https://doi.org/10.1093/nar/gkn655](https://doi.org/10.1093/nar/gkn655)                                                                                       |
| PPDB: Curated Plant Peptide Database                                                        | 3848(3848)                  | 529               | 2019          | [http://223.31.159.8/PlantPepDB](http://223.31.159.8/PlantPepDB)                             | [https://doi.org/10.1038/s41598-020-59165-2](https://doi.org/10.1038/s41598-020-59165-2)                                                                       |
| SATPDB: A Database of Structurally Annotated Therapeutic Peptides                           | 14569(19192)                | 1435              | Nov 02, 2015  | [https://webs.iiitd.edu.in/raghava/satpdb](https://webs.iiitd.edu.in/raghava/satpdb)         | [https://doi.org/10.1093/nar/gkv1114](https://doi.org/10.1093/nar/gkv1114)                                                                                     |

## 01 Database Properties

Analysis perform with the python libraries pandas, altair, Biopython, and Propy3 (https://pypi.org/project/propy3)

## 02 Similarity Comparison against SwissProt Database

The similarity analyzes eas performed with Diamond to find the similarity against SwissProt Database 2021.4

## 03 Clustering and Analysis 

The analysis was performed with MMseqs2.

## Figures description

**Figure 1. Antifungal peptides entries by database.** From each database were the antifungal peptides identified and fasta format applied conserving the original ID. 

**Figure 2. Distribution the peptide length.** From each database the peptide lenght was evaluated, the minimun peptide contain 1 aminoacids and the maximum is the 255 aminoacids, while the mean are less the 30 residues with the exception of the plant databases with 57.5, and 40.0, for PAMP, and PPDB, respectively. 

**Figure 3. Antifungal peptides aminoacids composition  by database.** From each database the aminoacod composition is presented, the red lines represent the fraction composition from ExPASy to the regular proteins. The residues with a over representation are Asparate and Glutamate, while the carged positive are Lysine, and Histidine, residues with particular properties are Cystein, Proline, and Glycine, and the only polar residues are Asparragine, and Methionine, finally, the only hydrophobic residue is Trypthophane. For other hands, the aminoacids with low fraction are Glutamine, Alanine and Phenylalanine.

**Figure 4. Antifungal sequences comparison with Swiss Protein Database similarity.** For the antifungal peptides from the six database with more entries were alignment with Swiss Prot database witd Diamond software and ultra-sensisitive parameters. The first query results was maintain with a total of 6,724 annotations for all databases with a maximun of 1790, and the minimun of 631. Interesting, the redundancy between the database similarity is low, only 144 protein for all annotations, these results reforced the requirement of consesus antifungal database. 

**Figure 5. Antifungal peptides from organism source.** The data is cut-off of 30 more abundant by Database organism source, the organism are from the metazoa (50), viridiplantae (45), and fungi (1), the most abundant sources are *H.sapiens*, A*.thaliana*, and *Odorrana sp.* 

**Figure 6.** **Antifungal peptides from gene-related.** The two groups of gene more abundant are the Antimicrobila peptides (AMP) and the Defensins family, both with wide antibacterial, fungicide and antiviral activities. 

**Figure 7. Non redundant antifungal peptides databases.** Redundant remotion and clustering was performed with MMseqs2, with a maximum of 6,196 unique peptides, and down the groups at 3,294 sequences wit high divergence (<30% identity).

**Figure 8. Consensus Antifungal Peptides Databases Clustering.** The clustering distribution for sizes are showed in distint level of identity cut-off (from 1.0 at 0.3).
