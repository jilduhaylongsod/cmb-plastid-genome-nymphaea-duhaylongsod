## Cell & Molecular Biology Lab Activity: Characterization of a Plastid Genome

Cell and Molecular Biology  

**Name:** Duhaylongsod, Jil M. 
**Course/Section:** BIO 300 - Cell and Molecular Biology - B

## 1. Purpose

   In this activity, you will select one plant genus with an available complete plastid genome, retrieve one complete plastid/chloroplast genome
from a public database, upload the genome to your own usegalaxy.org account, characterize its sequence and annotated genes, and document the complet
e exercise in a GitHub repository. 

## 2. Learning Outcomes 

Locate and verify a complete plastid/chloroplast genome in NCBI.  

Explain basic plastid-genome terms such as LSC, SSC, IR, CDS, rRNA, tRNA, intron, pseudogene, and GC content. 

Describe the overall organization and gene content of a selected plastid genome.  

Use Galaxy to upload a plastid genome and obtain basic sequence statistics. 

Compare plastid genomes with mitochondrial and nuclear genomes. 

Evaluate practical advantages and limitations of plastid genomes in biological studies.  Document the data source, analysis steps, results, and interpretation in GitHub. 

## 3. Choosing and Recording a Plant Genus 

<img width="390" height="116" alt="image" src="https://github.com/user-attachments/assets/19ef71fb-ffd9-4a77-b630-48092fcdcd92" />

**Figure 1.** NCBI record showing the complete Nymphaea nouchali chloroplast genome with accession number NC_059865.1 and the available GenBank and FASTA files.

## 4. Data Source and Genome Selection

| **Item** | **Information** |
|---|---|
| **Organism** | *Nymphaea nouchali* |
| **Family** | Nymphaeaceae |
| **Genome length** | 159,978 bp |
| **Topology** | Circular DNA |
| **NCBI accession** | NC_059865.1 |
| **Database** | NCBI Nucleotide / RefSeq |
| **Genome length** | 159,978 bp |
| **Sequence status** | Complete chloroplast genome |
| **Source** | NCBI Nucleotide, accession NC_059865.1 |
| **Associated source** | Zhang, H., Si, Y., Zhao, R., Sheng, Q., & Zhu, Z. (2023). *Complete chloroplast genome and phylogenetic relationship of Nymphaea nouchali (Nymphaeaceae), a rare species of water lily in China*. *Gene, 858*, 147139. |
| **Publication** | [PubMed — *Nymphaea nouchali* chloroplast genome publication](https://pubmed.ncbi.nlm.nih.gov/36621658/) |
| **NCBI record** | [NC_059865.1](https://www.ncbi.nlm.nih.gov/nuccore/NC_059865.1) |

<img width="422" height="208" alt="image" src="https://github.com/user-attachments/assets/581cb1c4-1b6a-4482-8cdc-0e3ce61c1ad5" />

**Figure 2.** NCBI FASTA view showing the DNA sequence of the complete Nymphaea nouchali chloroplast genome used for the analysis.

## 5. Files to Obtain
| **What to Get** | **Format** | **What You'll Use It For** | **File/Accession** |
|---|---|---|---|
| **1. Genome sequence** | FASTA | To upload the genome to Galaxy and obtain sequence statistics. | *Nymphaea nouchali* chloroplast genome, **NC_059865.1** |
| **2. Annotated genome** | GenBank/RefSeq | To find genes, introns, pseudogenes, coordinates, and other genome features. | *Nymphaea nouchali* chloroplast genome, **NC_059865.1** |
| **3. Source information** | NCBI record link/accession | To cite and document where the genome came from. | [NC_059865.1](https://www.ncbi.nlm.nih.gov/nuccore/NC_059865.1) |

## 6. Galaxy Workflow 

| **Statistic** | **Result** |
|---|---:|
| **Genome length** | 159,978 bp |
| **Number of sequence records** | 1 |
| **GC content** | 39.14% |
| **Complete plastome represented by one sequence** | Yes |

<img width="421" height="195" alt="image" src="https://github.com/user-attachments/assets/cea3daef-4e6a-4bbb-9deb-198f4ec0e602" />

**Figure 3.** Galaxy FASTA Statistics showing the results for the Nymphaea nouchali chloroplast genome, including its genome length and GC content. 

## 7. Plastid Genome Terms to Understand 

| **Term** | **Meaning** |
|---|---|
| **Plastid genome / Plastome** | The DNA found inside a plastid, such as a chloroplast. |
| **LSC** | Large Single-Copy region of the plastid genome. |
| **SSC** | Small Single-Copy region of the plastid genome. |
| **IR** | Inverted Repeat region; a plastid genome usually has two copies. |
| **CDS** | A DNA sequence that contains the information for making a protein. |
| **tRNA gene** | A gene that makes tRNA, which helps bring amino acids during protein production. |
| **rRNA gene** | A gene that makes ribosomal RNA, which is part of the ribosome. |
| **Intron** | A part of a gene that is removed from the RNA during processing. |
| **Pseudogene** | A gene-like sequence that has lost or may have lost its normal function. |
| **GC content** | The percentage of G and C bases in the DNA sequence. |
| **Accession** | A unique identification number given to a sequence in a database. |
| **Annotation** | Information added to a genome that identifies genes and other features. |

## 8. Required Plastid Genome Characterization 

| **Characteristic** | ***Nymphaea nouchali* chloroplast genome** |
|---|---|
| **Genus** | *Nymphaea* |
| **Species** | *Nymphaea nouchali* |
| **Family** | Nymphaeaceae |
| **Complete genome size in bp** | 159,978 bp |
| **GC content** | 39.14% |
| **Genome topology** | Circular DNA |
| **LSC** | 90,001 bp |
| **SSC** | 19,603 bp |
| **IR** | 50,374 bp total |
| **Total number of annotated genes** | 130 |
| **Number of protein-coding genes** | 85 |
| **tRNA genes** | 37 |
| **rRNA genes** | 8 |
| **Introns** | Present |
| **Pseudogenes** | No specific pseudogene count reported in the source |
| **Gene duplications** | Some genes are duplicated in the IR regions |
| **Overall organization** | Typical four-part structure: LSC–IR–SSC–IR |

**Gene Groups Identified**

| **Gene group** | **Examples / What to Look For** | **Main Function** |
|---|---|---|
| **Photosystem I genes (psa)** | psaA, psaB, psaI | Help in Photosystem I during photosynthesis. |
| **Photosystem II genes (psb)** | psbA, psbB, psbC, psbD | Help in Photosystem II during photosynthesis. |
| **ATP synthase genes (atp)** | atpA, atpB, atpE, atpF, atpH, atpI | Help make ATP, which provides energy. |
| **Cytochrome b6f genes (pet)** | petA, petB, petD, petG, petL, petN | Help with electron transfer during photosynthesis. |
| **rbcL** | rbcL | Helps fix carbon during photosynthesis. |
| **RNA polymerase genes (rpo)** | rpoA, rpoB, rpoC1, rpoC2 | Help make RNA from DNA. |
| **Ribosomal protein genes (rpl)** | rpl2, rpl14, rpl16, rpl20 | Help make the large part of the ribosome. |
| **Ribosomal protein genes (rps)** | rps2, rps3, rps4, rps15, rps19 | Help make the small part of the ribosome. |
| **rRNA genes (rrn)** | rrn16, rrn23, rrn4.5, rrn5 | Help make ribosomes. |
| **tRNA genes (trn)** | trnA, trnF, trnG, trnH, trnI | Help bring amino acids during protein production. |
| **matK** | matK | Helps with RNA processing. |
| **clpP** | clpP | Helps break down damaged or unwanted proteins. |
| **accD** | accD | Helps with fatty acid production. |
| **cemA** | cemA | Helps with chloroplast membrane functions. |

<img width="950" height="442" alt="image" src="https://github.com/user-attachments/assets/772c08db-863a-451a-bd73-42148075d2da" />

**Figure 4.** NCBI GenBank record showing the annotated Nymphaea nouchali chloroplast genome, including the genome information and annotated genes. 

## 9. Questions for the Student Report 

**1. Give the full scientific name, family, NCBI accession/version, database source, and complete plastid-genome size of your selected organism.**
The organism I selected is Nymphaea nouchali, which belongs to the Nymphaeaceae family. I got its complete chloroplast genome from NCBI Nucleotide,
with the accession number NC_059865.1. The genome is 159,978 bp long.

**2. What evidence shows that the sequence is a complete plastid/chloroplast genome rather than a barcode marker, genome fragment, or nuclear sequence?**
 The NCBI record shows that the sequence is a complete chloroplast genome. It is 159,978 bp long and has the usual chloroplast structure, which includes 
 the LSC, SSC, and two IR regions. It also has many annotated genes, such as protein-coding genes, tRNA genes, and rRNA genes. My Galaxy results also showed one
 sequence record with a length of 159,978 bp. These results show that the sequence is a complete chloroplast genome and not just a small gene or genome fragment.

**3. Describe the overall organization of the plastid genome. Does it contain the common LSC-IR-SSC-IR arrangement? Give the sizes of these regions when available.**
Yes. The Nymphaea nouchali chloroplast genome has the common LSC-IR-SSC-IR organization. The LSC region is 90,001 bp, the SSC region is 19,603 bp, and the two IR regions
together are 50,374 bp. The genome has a typical circular structure.

**4.Summarize the annotated gene content: total genes, protein-coding genes, tRNA genes, rRNA genes, and pseudogenes. Explain why genes located in the inverted-repeat regions may appear in two copies.**
The Nymphaea nouchali chloroplast genome contains 130 annotated genes. These include 85 protein-coding genes, 37 tRNA genes, and 8 rRNA genes. Genes located in the IR regions can appear in two copies because
the chloroplast genome contains two similar inverted-repeat regions. A gene located within one IR can therefore have a corresponding copy in the other IR.

**5. Choose at least eight protein-coding plastid genes from different functional groups. List each gene and briefly explain its biological function.**

| **Gene** | **Main Function** |
|---|---|
| **psaA** | Helps with Photosystem I during photosynthesis. |
| **psbA** | Helps with Photosystem II during photosynthesis. |
| **atpA** | Codes for part of ATP synthase, which helps produce ATP. |
| **petA** | Helps with electron transfer during photosynthesis. |
| **rbcL** | Codes for the large subunit of Rubisco and helps with carbon fixation. |
| **rpoB** | Part of the chloroplast RNA polymerase and helps make RNA. |
| **rpl2** | Codes for a ribosomal protein used in protein synthesis. |
| **matK** | Helps with RNA processing and maturation. |

**6. Identify important RNA and RNA-processing features. Include the rRNA genes, examples of tRNA genes, and at least two genes with introns if present in your genome.**
The genome contains 8 rRNA genes and 37 tRNA genes. Examples of rRNA genes include rrn16, rrn23, rrn4.5, and rrn5. Examples of tRNA genes include trnA, trnC, trnD, and trnF.
Several chloroplast genes in Nymphaea contain introns. Examples include atpF, rpl16, rpoC1, clpP, ycf3, and rps12. RNA processing removes introns from the transcript. 
Studies of Nymphaea plastomes specifically describe introns as important sources of sequence variation.

**7. Describe any pseudogenes, gene losses, duplications, rearrangements, or other unusual features reported for your plastid genome. If none are reported, state this clearly.**
The published genome study describes the Nymphaea nouchali chloroplast genome as relatively conservative and having the typical chloroplast structure. It does not report a specific
pseudogene count or a major genome rearrangement for this genome. The two IR regions cause some genes to occur in duplicated copies. The study also identified 136 simple sequence
repeat (SSR) sites and five highly variable regions that may be useful as molecular markers.

**8. What is the GC content of your plastid genome? Based on your Galaxy results and annotation, describe two other notable sequence or structural observations.**
The GC content of the Nymphaea nouchali plastid genome is 39.14%. My Galaxy analysis also showed that the genome is 159,978 bp long and is represented by one sequence record.

Two notable observations are:

The genome has the typical LSC-IR-SSC-IR structure, with two inverted-repeat regions.
The genome contains 130 annotated genes, including 85 protein-coding genes, 37 tRNA genes, and 8 rRNA genes.

**9. Compare plastid and mitochondrial genomes. Give at least five similarities and five differences, considering location, biological role, inheritance, genome organization, gene content, copy number, and evolutionary behavior.**

**Differences**
| **Feature** | **Plastid Genome** | **Mitochondrial Genome** |
|---|---|---|
| **Location** | Chloroplasts/plastids | Mitochondria |
| **Main function** | Mainly involved in photosynthesis | Mainly involved in cellular respiration and energy production |
| **Organization** | Usually has LSC, SSC, and two IR regions | Plant mitochondrial genomes have much more variable structures |
| **Size** | Usually relatively small and compact | Plant mitochondrial genomes can be much larger and vary greatly in size |
| **Gene content** | Contains many photosynthesis-related genes | Contains genes mainly related to respiration and mitochondrial functions |
| **Structural change** | Generally more conserved | Generally more structurally variable |
| **Common uses** | Species identification and plant phylogeny | Studies of mitochondrial function, inheritance, and plant evolution |

**Similarities**

Both have their own DNA.

Both are located in organelles outside the nucleus.

Both contain genes needed for important cellular functions.

Both occur in multiple copies within cells because cells usually contain multiple organelles.

Both originated from ancient endosymbiotic bacteria.

Both can be used in studies of evolution and phylogeny.

Both can be inherited through the cytoplasm rather than through the nuclear chromosomes.

**10. Explain the practical value of plastid genomes in research. List as many advantages as you can compared with the nuclear genome, including nuclear sex chromosomes where applicable, and also explain important limitations. Give one research question for
which plastid data would be useful and one for which nuclear genomic data would be more appropriate.**

Plastid genomes are useful because they are relatively small, have many conserved genes, and are easier to analyze than large nuclear genomes. They can be useful for species identification, DNA barcoding, plant classification, phylogenetic studies,
evolutionary research, and studying relationships between plant species. The N. nouchali study also identified highly variable chloroplast regions that could be useful as molecular markers.

**Advantages of plastid genomes**

They are much smaller than most nuclear genomes.

They contain many conserved genes.

Their structure is generally more conserved.

They are useful for comparing different plant species.

They are useful for studying plant evolutionary relationships.

They can help identify plant species.

They can provide useful molecular markers.

They are easier to analyze than very large nuclear genomes.

They can be useful when studying maternal inheritance in plants.

They do not have nuclear sex chromosomes, so they can be useful for questions that do not require nuclear sex-linked information.

**Limitations**

Plastid DNA represents only a small part of the total genetic information of a plant.

It usually does not show the full variation present in the nuclear genome.

Plastid inheritance is often uniparental, so it may not show both parental histories.

It cannot provide the same information as nuclear chromosomes.

It is not suitable for studying nuclear sex chromosomes.

Some evolutionary relationships may be different when using plastid data compared with nuclear data.

## Research question where plastid data would be useful

**How are different species of Nymphaea related to each other based on their chloroplast genomes?**

Plastid genomes are useful for this because chloroplast sequences can be compared between species to study their phylogenetic relationships. 
The N. nouchali study used chloroplast genome information for phylogenetic analysis.

## Research question where nuclear genomic data would be more appropriate

**How does genetic variation across the entire nuclear genome differ between male and female plants, including variation on nuclear sex chromosomes if the species has them?**

A nuclear genome would be more appropriate because plastid DNA does not contain the nuclear chromosomes or nuclear sex chromosomes and 
therefore cannot provide the complete nuclear genetic information.

| **Feature** | **Plastid genome** | **Mitochondrial genome** |
|---|---|---|
| **Cellular location** | Found inside the chloroplast. | Found inside the mitochondria. |
| **Main biological functions** | Mainly helps with photosynthesis and making some chloroplast proteins. | Mainly helps produce energy for the cell through cellular respiration. |
| **Typical genome organization** | Usually circular and has LSC, SSC, and two IR regions in many plants. | More variable and can have complex DNA structures in plants. |
| **Relative genome size** | Usually smaller, around 120–160 kb in many plants. *N. nouchali* is 159,978 bp. | Usually larger and can vary a lot between plant species. |
| **Gene content** | Contains genes for photosynthesis, protein production, tRNA, and rRNA. | Contains genes mainly involved in energy production and mitochondrial functions. |
| **Copy number** | Usually has many copies in a cell. | Can also have many copies, but the number can vary. |
| **Inheritance** | Usually passed from the mother in many flowering plants, but there are exceptions. | Usually passed from the mother in many flowering plants, but there are exceptions. |
| **Recombination / structural change** | Usually more stable, but some changes can happen. | More changeable and can have many rearrangements. |
| **Mutation / substitution pattern** | Usually more conserved and changes more slowly than nuclear DNA. | Can vary between plant species and can have many structural changes. |
| **Common research applications** | Used to study plant species, evolution, and relationships between plants. | Used to study plant evolution, energy-related genes, inheritance, and mitochondrial changes. |


## References:

NCBI nucleotide: https://www.ncbi.nlm.nih.gov/nuccore/NC_059865.1?report=fasta

NCBI Genbank: https://www.ncbi.nlm.nih.gov/nuccore/NC_059865.1?report=genbank

Use galaxy org: https://usegalaxy.org/u/jilduhaylongsod/h/plastid-nymphaea-duhaylongsod

Use galaxy training Network: https://usegalaxy.org/?tool_id=toolshed.g2.bx.psu.edu%2Frepos%2Fiuc%2Ffasta_stats%2Ffasta-stats%2F2.0&version=latest

Github: https://github.com/jilduhaylongsod/cmb-plastid-genome-nymphaea-duhaylongsod.git


Zhang, H., Si, Y., Zhao, R., Sheng, Q., & Zhu, Z. (2023). Complete chloroplast genome and phylogenetic relationship of Nymphaea nouchali (Nymphaeaceae), a rare species of water lily in China. Gene, 858, 147139.  https://doi.org/10.1016/j.gene.2023.147139 



