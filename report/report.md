# Bioinformatic characterization of the *PMM2* p.Thr237Met variant: sequence conservation and structural comparison

Adriana Dotsenko, Dàlia Jordan, Salomé Murillo, Elsa Rosado, Noah Quixal

*Facultat d'Informàtica de Barcelona, Universitat Politècnica de Catalunya, Barcelona, Spain*

## Abstract

**Background -** Phosphomannomutase 2 (PMM2) is an enzyme that functions as a homodimer and plays an essential role in N-glycosylation by converting mannose-6-phosphate into mannose-1-phosphate. Pathogenic variants in PMM2 cause PMM2-congenital disorder of glycosylation (PMM2-CDG), an autosomal recessive disease that affects several organs, particularly the nervous system, due to impaired protein glycosylation. The p.Thr237Met (T237M) variant lies in the α9 helix of the core domain, where Thr237 forms a hydrogen bond with Thr16. This study aimed to characterize the T237M variant and investigate the conservation of PMM2 across *Homo sapiens*, *Vicugna pacos*, and *Leishmania mexicana* using bioinformatics tools.

**Results -** Sequence alignment identified a single-nucleotide substitution, c.710C>T, which changes threonine to methionine at position 237. The structural comparison between wild-type (Protein Data Bank [PDB]: 7O1B) and T237M (PDB: 7O58) PMM2 showed that both structures are highly similar, with a global root-mean-square deviation (RMSD) of 0.351 Å and local backbone displacement of 0.262 Å at position 237. This indicates that the substitution does not substantially alter the overall protein structure. Comparisons across species revealed 90% protein sequence identity between human PMM2 and *V. pacos* over 87% of the human sequence, compared with 57% identity between human PMM2 and *L. mexicana* over 97% coverage. The FDVDGTL motif, which contains important catalytic and magnesium-binding residues, was conserved in all three species. Functional residues annotated in UniProt were also conserved in *L. mexicana* and the analysed *V. pacos* isoform. Thr237 and several nearby residues were conserved in *L. mexicana*, but it was not possible to assess whether this position was conserved in *V. pacos* because the studied isoform did not contain this region. The structural comparison between human PMM2 and *L. mexicana* PMM2 showed an overall RMSD of 1.66 Å.

**Conclusions -** These findings suggest that although T237M does not appear to cause major changes in the protein's overall structure, replacing threonine with the larger, nonpolar methionine may disrupt the hydrogen bond with Thr16 and affect local interactions and enzyme function. Further experiments are needed to confirm these potential effects.


## Keywords

PMM2, PMM2-CDG, T237M, missense variant, sequence alignment

## Background

Phosphomannomutase 2 (PMM2) is a protein whose function is to convert mannose-6-phosphate (M6P) into mannose-1-phosphate (M1P) and requires glucose-1,6-bisphosphate (G16BP) or mannose-1,6-bisphosphate (M16BP) as an activator. The M1P is a precursor of guanosine diphosphate (GDP)-mannose, which gives mannose to build dolichol-phosphate-mannose (Dol-P-M), which in turn fuels the construction of the glycan that attaches to proteins, N-glycosylation (Oliveira et al. 2025). PMM2 is only active as a dimer, a protein composed of two chains joined together to form a functional unit. PMM2 is a homodimer: its two chains are identical and each one is divided by zones depending on the amino acid positions. Said zones are: the core domain, the cap domain, and the linkers 1 and 2 (Briso-Montiano et al. 2022).

The two subunits do not have the same conformation in the dimer and differ in 3D. One of them has its core closer to the cap than the other. This should be expected for an enzyme that opens and closes to trap its substrate, enabled by the linkers, a proposition based on the crystal structure (Briso-Montiano et al. 2022).

PMM2-congenital disorder of glycosylation (PMM2-CDG) is an autosomal recessive disease and the most prevalent N-glycosylation disorder. The disorder is caused by variants in PMM2 that reduce its activity. When PMM2 activity is reduced, the absence of M1P means GDP-mannose is lacking, so proteins receive fewer glycans and become hypoglycosylated. This translates into a malfunction of several organs, its primary impact being on the nervous system causing disorders such as ataxia or epilepsy (Oliveira et al. 2025).

Furthermore, a way to classify missense variants into six different mechanisms of impact to predict the effects on the function and structure of PMM2 was proposed (Briso-Montiano et al. 2022). These mechanisms of impact were activator binding, catalysis, dimerization, cap folding, core folding, and linker 2. Forty-one of these pathogenic missense variants taken from ClinVar were analysed using the wild-type (WT) PMM2 structure (Protein Data Bank [PDB] entry 7O4G) and the PyMOL mutagenesis tool, using the classification proposed by Briso-Montiano et al. as a basis (Oliveira et al. 2025).

The variant studied in this report is the p.Thr237Met (T237M). This variant was found in nine out of 137 patients with PMM2-CDG (Pajusalu et al. 2024). It is located on the α9 helix of the core domain of each subunit. Based on the superposition of the WT and the T237M, there are no major changes in the overall fold. The dimers are essentially identical, with low root-mean-square deviation (RMSD) values. The side chain of Thr237 forms a hydrogen bond with Thr16, which is situated on the loop that coordinates Mg-1 (the catalytic magnesium ion). By replacing threonine with methionine, the bond is lost, affecting both stability and catalysis (Briso-Montiano et al. 2022).

Although the structural effect of T237M on PMM2 has been described, it is less clear whether position 237 is conserved across species. The objective of this report is to identify the variant at the gene and protein level and compare the human PMM2 with two homologues from *Leishmania mexicana* and *Vicugna pacos* using bioinformatics tools.

## Results

### Identification of PMM2 and the disease-associated variant

A search with the Basic Local Alignment Search Tool (BLAST) (National Center for Biotechnology Information [NCBI] 2026), using BLASTn with the reference coding sequence (CDS), identified the RefSeq record NM_000303.3, and BLASTp with the reference protein identified NP_000294.1. Both records correspond to the gene *PMM2* (Gene ID 5373), located at 16p13.2 on chromosome 16 and composed of eight exons.

The alignment of the reference and mutant CDS covered the full length of both sequences (741 nt) without gaps and showed 740 identical positions out of 741 (99%). The only difference was a single-nucleotide substitution at position 710, where the reference cytosine is replaced by a thymine (c.710C>T) (Figure 1A). This change converts codon 237 from ACG to ATG.

At the protein level, the reference and mutant sequences (246 residues) were identical at 245 positions out of 246 (99%), again without gaps. The only difference was the replacement of threonine by methionine at position 237 (p.Thr237Met) (Figure 1B). This substitution replaces a small, polar residue with a larger, nonpolar one of the same charge, so position 237 loses the hydroxyl group that allows threonine to donate hydrogen bonds.

![Figure 1](../figures/Figura_1_Report.png)

**Figure 1. Identification of the T237M variant.** (A) Pairwise BLASTn alignment between the wild-type CDS (Query) and the mutant CDS, showing the region from nucleotide 661 to 720. (B) Pairwise BLASTp alignment between the wild-type protein (Query) and the mutant protein, showing the region from residue 181 to 240. In both panels, the upper line shows the wild-type sequence and the lower line shows the mutant sequence, where dots indicate positions identical to the wild type. The red box marks the only difference between the two sequences: cytosine replaced by thymine at nucleotide 710 (A) and threonine replaced by methionine at residue 237 (B). The header of each panel summarizes the alignment, with 740/741 identical nucleotides and 245/246 identical residues, and no gaps.

### Structural comparison of wild-type and T237M PMM2

The superposition of the wild-type (7O1B) and T237M (7O58) structures gave a global root-mean-square deviation (RMSD) of 0.351 Å, and the local backbone displacement at position 237 was 0.262 Å (Figure 2). According to UniProt (O15305), Thr237 lies in the last α-helix of the protein (residues 234-245), 11 residues after the predicted second Mg<sup>2+</sup>-binding site (Phe221, Asp223, and Thr226).

![Figure 2](../figures/Figura_2_Report.png)

**Figure 2. Local structure of wild-type and T237M PMM2 at position 237.** Superposition of the wild-type structure (PDB 7O1B, light blue) and the T237M structure (PDB 7O58, yellow), centred on the α-helix that contains residue 237. Residue 237 is highlighted in dark blue in the wild type and in orange in the mutant, and its side chain is shown as sticks: threonine in the wild type and methionine in the mutant, whose longer side chain contains a sulphur atom (yellow stick). The two backbones overlap almost completely in this region (local backbone displacement of 0.262 Å). Image obtained from internal sources.

### Cross-species comparison of gene and protein sequences

The human *PMM2* sequences were compared with those of *Leishmania mexicana* (XM_003874496.1 and XP_003874545.1) and *Vicugna pacos* (XM_072942246.1 and XP_072798347.1). The *V. pacos* record corresponds to a predicted mRNA (transcript variant X7) of 5795 nt, in which only nucleotides 62-742 (681 nt) are coding; the rest are untranslated regions.

At the CDS level, the human sequence was highly similar to that of *V. pacos*, whereas with *L. mexicana* BLASTn aligned only one short region (nucleotides 516-668, which encode residues 172-223) (Table 1). Several nucleotide differences between species did not change the encoded amino acid. For example, codons 2, 3, 4, 12, 13, and 14 differ between human and *V. pacos* but encode the same residues in both species.

At the protein level, similarity with both species extended along almost the whole sequence, including *L. mexicana*, for which the CDS alignment had covered only a small part of the gene (Table 1). The *V. pacos* protein contains a 12-residue insertion after human position 59 and ends after the position equivalent to human residue 213, so it lacks the region corresponding to human residues 214-246.

**Table 1. Pairwise similarity of PMM2 between human and two other species.**

| Species compared with *H. sapiens* | CDS identity | CDS query coverage | Protein identity | Protein positives | Protein query coverage |
| --- | --- | --- | --- | --- | --- |
| *L. mexicana* | 70% | 21% | 57% | 71% | 97% |
| *V. pacos* (isoform X7) | 91% | 62% | 90% | 92% | 87% |

Values were obtained with NCBI BLAST (‘Align two or more sequences’), using BLASTn for the CDS and BLASTp for the protein sequences, with the human sequence as query. Identity is the percentage of identical positions in the aligned region; positives also include positions with amino acids of similar properties; query coverage is the percentage of the human sequence included in the alignment. Identity percentages include gap positions.

In the multiple alignment of the three proteins, the N-terminal stretch FDVDGTL (residues 11-17), which contains the DxD motif, was identical in the three species (Figure 3). All the residues annotated as functional in UniProt (O15305) were also identical in *L. mexicana*: the catalytic nucleophile (Asp12), the proton donor/acceptor (Asp14), the residues of the two predicted Mg<sup>2+</sup>-binding sites (Asp12, Asp14, and Asp209; Phe221, Asp223, and Thr226), and the residues that bind mannose 1-phosphate (Arg21, Arg123, Arg134, Arg141, Ser179, and Asp181). In *V. pacos*, all the functional residues present in its sequence were conserved.

Thr237 was identical in *L. mexicana*, and so were several neighbouring positions (Gly228, Ser230, Val231, and Asp236). This position could not be assessed in *V. pacos*, because isoform X7 lacks this region (Figure 3).

![Figure 3](../figures/Figura_3_Report.png)

**Figure 3. Multiple alignment of the PMM2 protein in three species.** Clustal Omega alignment of the PMM2 protein of *L. mexicana* (XP_003874545.1, first row of each block), *H. sapiens* (PMM2_protein_WT, second row), and *V. pacos* (XP_072798347.1, third row). Numbers on the right indicate the position of the last residue of each row in each sequence, and dashes indicate gaps. Symbols below each block indicate identical residues in the three sequences (\*), residues with strongly similar properties (:), and residues with weakly similar properties (.). Green box: FDVDGTL motif. Blue boxes: functional residues annotated in UniProt (O15305), corresponding to the catalytic site, the two Mg<sup>2+</sup>-binding sites, and the mannose 1-phosphate-binding site. Red box: position 237, mutated in the T237M variant.

### Structural comparison between human and *L. mexicana*

The superposition of the human and *L. mexicana* PMM2 structures gave a global RMSD of 1.66 Å, although the two sequences share only 57% identity (Figure 4). The largest structural differences were concentrated in one region of the protein, while the rest of the two structures overlapped closely (Figure 4A). The secondary structure was almost identical in the two species, except for the stretch between human residues 65 and 84. At position 237, the local backbone displacement between the two species was 1.465 Å, and the residue was located in an α-helix in both structures.

![Figure 4](../figures/Figura_4_Report.png)

**Figure 4. Structural comparison of human and *L. mexicana* PMM2.** (A) Superposition of the two structures coloured by local backbone displacement: white indicates regions that overlap closely, and increasingly intense red indicates regions that are further apart in space. Yellow segments were excluded from the superposition. (B) The same superposition coloured by species, with the human structure in blue and the *L. mexicana* structure in green. Image obtained from internal sources.

## Discussion

### Identification of PMM2 and the disease-associated variant

The variant is a nucleotide substitution in *PMM2*, from C to T at position 710 (c.710C>T). It is a missense variant that changes codon ACG to ATG, so methionine is encoded instead of threonine. Although both amino acids are uncharged, their properties differ: threonine is polar and its hydroxyl group allows it to form hydrogen bonds, whereas methionine is nonpolar and lacks this group, which may disrupt protein interactions. The side chain of Thr237 forms a hydrogen bond with Thr16, located in the loop that coordinates Mg-1 (magnesium ion 1). The loss of this bond has been reported to affect the stability of the protein and its enzymatic activity, leading to malfunction (Briso-Montiano et al. 2022). However, the variant keeps a structure similar to that of the wild-type protein, so a change in the sequence does not necessarily alter the global structure.

Residue 237 is located in the α9 helix (residues 234–245), not in an Mg<sup>2+</sup>-binding site, but 11 residues after Thr226. The substitution is therefore unlikely to have a direct effect on Mg<sup>2+</sup> binding. Moreover, since the interactions of the residue were not analysed, it could not be demonstrated that any effect results from the loss of the hydrogen bond.

PMM2 converts mannose-6-phosphate into mannose-1-phosphate, which is needed to produce GDP-mannose for glycosylation. An altered PMM2 activity could therefore affect this reaction and contribute to PMM2-CDG (Oliveira et al. 2025). The clinical relevance of T237M is supported by its presence in nine of 137 patients with PMM2-CDG (Pajusalu et al. 2024). The disease affects the nervous system and causes, for example, epilepsy and ataxia (Oliveira et al. 2025), but how this variant leads to the disease could not be analysed here.

### Structural comparison of wild-type and T237M PMM2

The superposition of 7O1B (wild-type) and 7O58 (mutant) gave a low RMSD (0.351 Å), and the local backbone displacement at position 237 was also low (0.262 Å). This means that the amino acid change did not have a noticeable impact on the backbone, since the two structures are very similar. However, RMSD only reflects positions and does not identify changes in side-chain interactions, so subtle changes may still have consequences for functionality and enzymatic activity.

### Cross-species comparison of gene and protein sequences

The comparisons with *Leishmania mexicana* and *Vicugna pacos* showed that the sequences are conserved, which suggests that they are important for function. *V. pacos* was the most similar to human PMM2, with 91% nucleotide identity (although only 62% of the sequence was aligned) and 90% protein identity over 87% of the sequence. The 87% protein coverage is explained by the fact that it is an isoform (X7) whose protein ends at residue 213 and lacks residues 214 to 246. This does not explain the low CDS coverage, which probably reflects regions that BLASTn could not align.

For *L. mexicana*, only 21% of the CDS could be aligned, with 70% identity. At the protein level, 97% of the sequence was aligned, with 57% identity and 71% positives (positives include identical residues and different residues with similar chemical properties). It is therefore expected that the percentage of positives is higher than that of identity. This suggests that the nucleotide sequences of *L. mexicana* have diverged more than its amino acid sequences.

Codons 12, 13, and 14 of *V. pacos* differ from those of *H. sapiens* but encode the same amino acids. These codons belong to the FDVDGTL motif (residues 11–17), which was identical in the three species. This motif contains the DxD motif, which includes Asp12 and Asp14, residues that participate in magnesium binding. According to UniProt, all the functional residues were conserved in *L. mexicana*. This suggests that these positions are important for the structure or function of the protein, and that their sequence has been conserved by selection because a mutation could be detrimental. Thr16, located in the motif, was conserved in the three species, and Thr237 was conserved in *L. mexicana*, which suggests that the interaction between Thr237 and Thr16 could be functionally relevant. In *V. pacos*, Thr237 could not be examined because the isoform lacks this region. Nevertheless, conservation is only evidence that these regions are significant, and further experiments would be needed to reach a firm conclusion.

### Structural comparison between human and *L. mexicana*

The RMSD between the human and *L. mexicana* structures was 1.66 Å, which indicates that the two structures are similar despite sharing only 57% sequence identity. This suggests that a large percentage of different amino acids does not necessarily change the structure of a protein drastically. Although the sequences differ, both proteins have a similar fold, with the main differences between residues 65 and 84. A similar fold does not imply that the activity is the same, since local interactions and differences in side chains might affect function.

Residue 237 is located in an α-helix in both structures, with a local backbone displacement of 1.465 Å, which indicates a small difference in position. This value is higher than the 0.262 Å obtained when comparing the wild-type and T237M structures, probably because the *L. mexicana* sequence has diverged more. However, a positional variation in this region does not demonstrate a change in the stability of the helix.

For *V. pacos*, which was very similar to the human PMM2 sequence, the protein sequence including residue 237 was not available. It was therefore not possible to study whether the residue is conserved or to compare it structurally.

### Limitations

This study has several limitations. First, RMSD and local backbone displacement provide information only about differences in atomic positions, not about function. No analysis was performed of the enzymatic activity or of the hydrogen bond between Thr237 and Thr16, so it cannot be determined whether the structural differences affect PMM2 function.

Second, in the comparison of species, not all the regions of the sequences were available, so the analysis depended on the data obtained. For instance, only 21% of the *L. mexicana* CDS could be aligned with the human CDS, which limits the conclusions. Furthermore, the *V. pacos* isoform lacks the region that includes residue 237, so the conservation of this residue could only be examined in the other species. In addition, the identity percentages include gap positions in the alignment, so they should be interpreted carefully.

Lastly, the analyses cannot fully confirm the mechanism of the T237M variant, which has been reported to affect PMM2 function. Further experiments on protein stability and activity would be needed to clarify how the substitution affects the protein and to determine whether the function is conserved between species, given that the structural comparison revealed similar folds.

## Conclusions

In this project, a variant of the *PMM2* gene was studied at the nucleotide and protein level and compared with its homologues in *Leishmania mexicana* and *Vicugna pacos* using bioinformatics tools. The main conclusions are the following. The mutant and the wild-type sequences differ in one position. The variant is a nucleotide substitution (c.710C>T) in the *PMM2* sequence which makes a change in codon 237, replacing the amino acid threonine with methionine. This substitution did not have a major impact on the structure of PMM2 (global RMSD of 0.351 Å and local backbone displacement of 0.262 Å). Residue 237 is not located in the Mg<sup>2+</sup> binding sites, so an alteration in catalytic activity may occur indirectly through changes in the protein's structure rather than directly from the active site. Also, the FDVDGTL motif, which contains the DxD motif, was found to be conserved in the three species. Thr237 was conserved in *L. mexicana* but it could not be determined in *V. pacos* because of the isoform. *H. sapiens* and *L. mexicana* showed a similar fold (1.66 Å) despite sharing 57% sequence identity, which suggests that the PMM2 structure is largely conserved in *L. mexicana*. The loss of the hydrogen bond between Thr16, in the loop that coordinates the magnesium ion, and Thr237 may alter PMM2 (Briso-Montiano et al. 2022). However, more specific analysis of the hydrogen bond, enzymatic activity, and measurements of the stability of the variant would be needed to confirm this.

## Methods

For the analysis of protein structure and differences, UniProt record O15305 (UniProt Consortium 2026) was used as the reference for the human WT PMM2 protein, and PDB records 7O1B and 7O58 (RCSB Protein Data Bank 2026) were used for the human WT and mutant PMM2 proteins, respectively.

For the purpose of sequence alignments, FASTA sequences for the human PMM2 WT and mutant sequences, both coding sequence (CDS) and protein sequences, were provided by internal sources and can be found in the supplemental information.

For the homologues, FASTA files associated with the following NCBI accessions were used: for *Leishmania mexicana*, CDS XM_003874496.1 and protein XP_003874545.1, and for *Vicugna pacos*, CDS XM_072942246.1 and protein XP_072798347.1. These were found by setting the human PMM2 WT CDS in the Query box of BLASTn, and limiting the search to each of the two species while choosing the algorithm for ‘somewhat similar sequences’. Analogously for the protein sequences, they were found by setting the human PMM2 protein in the Query box of BLASTp, and limiting the search to each of the two species while choosing the algorithm for ‘somewhat similar sequences’.

To generate the sequence alignments between the human WT and mutant sequences, BLAST (National Center for Biotechnology Information 2026) was used. For the CDSs, this was done with BLASTn (‘Align two or more sequences’), copying the human WT CDS FASTA file into the Query box and the human mutant CDS into the Subject Sequence box, and then running the alignment. Afterwards, the process was repeated with the BLASTp interface, using the human WT and mutant protein sequences, in order to compare the protein sequences.

To analyse the WT versus mutant sequence alignments, the ‘Pairwise with dots for alignments’ view was chosen. This view sets the ‘Query’ as the reference above, with the ‘Subject’ sequence below. The ‘Subject’ sequence shows dots at the aligned residues that are identical in both sequences and, when they are not, specifies the differing residue. Each sequence alignment was accompanied by its identity and coverage values, calculated by BLAST.

For the homologue comparison, the first step was to cut the nucleotides before the start codon and after the stop codon from the *V. pacos* FASTA file, as it was otherwise about 5000 nucleotides longer than the CDSs of the other two species. The alignment itself was done with the Clustal Omega multiple sequence alignment tool (version 1.2.4) (European Bioinformatics Institute 2026). Two alignments were done separately. First, the CDS alignment was done by adding the human, *L. mexicana*, and *V. pacos* CDSs from their respective FASTA files, with their FASTA headers, into the ‘Input sequence’ box. Secondly, the protein alignment was done by repeating the process with the protein FASTA files.

The Clustal Omega sequence alignment tool marks under each aligned set of nucleotides whether the elements of the position are the same (\*) or not ( ). For proteins, in the case that the amino acids are different, it also differentiates whether they are from similar (:) or vaguely similar (.) physicochemical groups. These marks were used to differentiate the highly conserved regions from the less conserved regions.

The analysis of the aligned sequences was complemented with a report on the structural alignment of the human PMM2 WT protein sequence and the *L. mexicana* protein sequence, provided by internal sources. This report includes statistical data on: sequence identity, percentage of residues with coinciding physicochemical class, global RMSD, primary and secondary structure alignment, local backbone displacement, and 3D imaging of the two proteins superimposed. It also includes information on the disease-associated variant of the protein, including the protein mutation type and location, local backbone displacement of the variant, global WT-mutant RMSD, and imaging of the WT and mutant proteins superimposed specifically around the mutated region.

Generative artificial intelligence (AI) was used as a support tool during the preparation of this report. Claude (Anthropic) was used to explain bioinformatics and biological concepts, to review and correct drafts written by the authors (grammar, spelling, consistency of terminology and of data between sections, and adherence to the journal style), to suggest alternative wording for some sentences, which the authors then evaluated and edited, to advise on how to search for and cite the literature, and to format the document and the reference list. All analyses, results, and interpretations were performed and verified by the authors against the original data and the cited sources, and all commits to the project repository were made by the authors. The authors take full responsibility for the content of this report.

## Abbreviations

- 3D: three-dimensional
- AI: artificial intelligence
- Arg21: arginine at position 21 of the protein sequence
- Arg123: arginine at position 123 of the protein sequence
- Arg134: arginine at position 134 of the protein sequence
- Arg141: arginine at position 141 of the protein sequence
- Asp12: aspartic acid at position 12 of the protein sequence
- Asp14: aspartic acid at position 14 of the protein sequence
- Asp181: aspartic acid at position 181 of the protein sequence
- Asp209: aspartic acid at position 209 of the protein sequence
- Asp223: aspartic acid at position 223 of the protein sequence
- Asp236: aspartic acid at position 236 of the protein sequence
- BLAST: Basic Local Alignment Search Tool
- CDG: congenital disorder of glycosylation
- CDS: coding sequence
- Dol-P-M: dolichol-phosphate-mannose
- DxD: Asp-x-Asp motif (x = any amino acid)
- G16BP: glucose-1,6-bisphosphate
- GDP: guanosine diphosphate
- Gly228: glycine at position 228 of the protein sequence
- *H. sapiens*: *Homo sapiens*
- *L. mexicana*: *Leishmania mexicana*
- M16BP: mannose-1,6-bisphosphate
- M1P: mannose-1-phosphate
- M6P: mannose-6-phosphate
- Met: methionine
- Mg-1: magnesium ion 1
- Mg²⁺: magnesium cation
- mRNA: messenger RNA
- NCBI: National Center for Biotechnology Information
- nt: nucleotide
- OMIM: Online Mendelian Inheritance in Man
- PDB: Protein Data Bank
- Phe221: phenylalanine at position 221 of the protein sequence
- PMM2: phosphomannomutase 2
- PMM2-CDG: PMM2-congenital disorder of glycosylation
- RMSD: root-mean-square deviation
- Ser179: serine at position 179 of the protein sequence
- Ser230: serine at position 230 of the protein sequence
- T237M: p.Thr237Met variant (threonine replaced by methionine at position 237 of the protein sequence)
- Thr: threonine
- Thr16: threonine at position 16 of the protein sequence
- Thr226: threonine at position 226 of the protein sequence
- Thr237: threonine at position 237 of the protein sequence
- *V. pacos*: *Vicugna pacos*
- Val231: valine at position 231 of the protein sequence
- WT: wild-type

## Declarations
### Availability of data and materials

The datasets generated and analyzed during this study (FASTA sequences, alignment outputs, figures and analysis notes) are available in the GitHub repository G12A\_PMM2\_CDG\_IB\_2026 ([https\://github.com/daliajordan/G12A\_PMM2\_CDG\_IB\_2026](https://github.com/daliajordan/G12A_PMM2_CDG_IB_2026)). The sequences and structures analyzed were obtained from public databases: UniProt (O15305), the Protein Data Bank (7O1B and 7O58) and NCBI (accessions given in Methods).

### Authors' contributions

- AD: Defined the project objectives and the roles of the team, retrieved gene–disease information from OMIM and protein annotation from UniProt, wrote the limitations, the Discussion and the Conclusions.  
- DJ: Created and maintained the GitHub repository, built the Gantt chart, performed the sequence alignments and the conservation analysis, prepared the figures, wrote the Results, and designed the outline of the report.  
- SM: Searched the literature (reviews and original papers), managed the references, wrote the Background and reviewed the report. 
- ER: Carried out the risk analysis, identified the protein domains with InterPro, selected the wild-type and variant structures in the Protein Data Bank (PDB) and wrote the Abstract. 
- NQ: Co-built the Gantt chart, compared the wild-type and variant structures, interpreted the evolutionary comparison, prepared the figures, wrote the Methods and  handled the final submission. 

All authors read and approved the final manuscript.


## References

1. \*\*\*Briso-Montiano A *et al.* Insight on molecular pathogenesis and pharmacochaperoning potential in phosphomannomutase 2 deficiency, provided by novel human phosphomannomutase 2 structures. *J Inherit Metab Dis* 2022;45:318–33.
2. European Bioinformatics Institute. *Clustal Omega*. https://www.ebi.ac.uk/jdispatcher/msa/clustalo (23 October 2026, date last accessed).
3. National Center for Biotechnology Information. *Basic Local Alignment Search Tool (BLAST)*. https://blast.ncbi.nlm.nih.gov (22 October 2026, date last accessed).
4. \*\*Oliveira T *et al.* A comprehensive update of genotype–phenotype correlations in PMM2-CDG: insights from molecular and structural analyses. *Orphanet J Rare Dis* 2025;20:207.
5. \*Pajusalu S *et al.* Genotype/phenotype relationship: lessons from 137 patients with PMM2-CDG. *Hum Mutat* 2024;2024:8813121.
6. RCSB Protein Data Bank. *RCSB PDB: Protein Data Bank*. https://www.rcsb.org (23 October 2026, date last accessed).
7. UniProt Consortium. *UniProt: the Universal Protein Knowledgebase*. https://www.uniprot.org (22 October 2026, date last accessed).
