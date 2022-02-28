# CAFPdb
A consolidated database of antifungal peptides.

## Stages of Analysis

* 00 Data Collection
* 01 Database Properties
* 02 Similarity Comparison against SwissProt Database
* 03 Clustering and Analysis 

The consensus antifungal peptide database contains 6,196 unique sequences.

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

Analysis performed with the Python libraries Pandas, Altair, Biopython, and Propy3 (https://pypi.org/project/propy3)

## 02 Similarity Comparison against Swiss-Prot Database

The similarity analyzes was performed with Diamond to find the similarity against SwissProt Database 2021.4

## 03 Clustering and Analysis 

The analysis was performed with MMseqs2.

## Figures description

**Figure 1. Antifungal peptides entries in each database.** Fasta formatted peptides from each database were counted by keeping original IDs. 

**Figure 2. Peptide length distribution.** FPeptide length was determined for each individual database. The minimum length is 1 amino acid and the maximum length is of 255 amino acids, with an average value of 30 residues. 

**Figure 3. Amino acid composition of antifungal peptides from each individual database.** For each individual database the amino acid composition is presented, with red lines representing the average composition in ExPASy for regular proteins. Overrepresented amino acids in different databases include negatively charged Aspartate and Glutamate, positively charged Lysine, in addition to Histidine Cysteine, Proline, and Glycine, and polar residues Asparagine and Methionine. Tryptophane is the only hydrophobic residue that is present in a higher proportion. Amino acids with low representation include Glutamine, Alanine and Phenylalanine.

**Figure 4. Sequence similarity comparison of antifungal peptides with Swiss Protein Database.** Antifungal peptides from the six database with more entries were aligned with Swiss Prot database using Diamond software with ultra-sensitive parameters. A total of 6,724 annotations were obtained from the query for all databases, with a maximum of 1790, and the minimum of 631. Interesting, the redundancy between the databases is low (144 protein for all annotations), providing support to the consolidation analysis. 

**Figure 5. Source organism of the antifungal peptides.** The analysis was carried out with a cut-off of 30 more abundant source organisms in the Database, including organisms from the Metazoa (50), Viridiplantae (45) and Fungi (1). The most abundant sources are *H. sapiens*, *A .thaliana* and *Odorrana sp.* 

**Figure 6. Source protein of antifungal peptides.** The two more abundant groups of source proteins are the Antimicrobial peptides (AMP) and the Defensins families, both with a wide antibacterial, antifungal and antiviral activities. 

**Figure 7. Non-redundant antifungal peptide database.** Redundancy removal and clustering were performed with MMseqs2, yielding a maximum of 6,196 unique peptides.  A total of 3,294 sequences wit high divergence (<30% identity) were eliminated.

**Figure 8. Clustering of antifungal peptides from all the databases.** Clusters distribution in terms of the sizes at different levels of identity, with cut-off values ranging from 1.0 at 0.3.
