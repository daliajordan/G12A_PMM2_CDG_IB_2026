## Results

### Identification of PMM2 and the disease-associated variant

A BLASTn search with the reference coding sequence (CDS) identified the RefSeq record NM_000303.3, and a BLASTp search with the reference protein identified NP_000294.1. Both records correspond to the gene *PMM2* (Gene ID 5373), located at 16p13.2 on chromosome 16 and composed of eight exons.

The alignment of the reference and mutant CDS covered the full length of both sequences (741 nt) without gaps and showed 740 identical positions out of 741 (99%). The only difference was a single-nucleotide substitution at position 710, where the reference cytosine is replaced by a thymine (c.710C>T) (Figure 1A). This change converts codon 237 from ACG to ATG.

At the protein level, the reference and mutant sequences (246 residues) were identical at 245 positions out of 246 (99%), again without gaps. The only difference was the replacement of threonine by methionine at position 237 (p.Thr237Met) (Figure 1B). This substitution replaces a small, polar residue with a larger, nonpolar one of the same charge, so position 237 loses the hydroxyl group that allows threonine to donate hydrogen bonds.

![Figure 1](../figures/Figura_1_Report.png)

**Figure 1. Identification of the T237M variant.** (A) Pairwise BLASTn alignment between the wild-type CDS (Query) and the mutant CDS, showing the region from nucleotide 661 to 720. (B) Pairwise BLASTp alignment between the wild-type protein (Query) and the mutant protein, showing the region from residue 181 to 240. In both panels, the upper line shows the wild-type sequence and the lower line shows the mutant sequence, where dots indicate positions identical to the wild type. The red box marks the only difference between the two sequences: cytosine replaced by thymine at nucleotide 710 (A) and threonine replaced by methionine at residue 237 (B). The header of each panel summarizes the alignment, with 740/741 identical nucleotides and 245/246 identical residues, and no gaps.

### Structural comparison of wild-type and T237M PMM2

The superposition of the wild-type (7O4G) and T237M (7O58) structures gave a global root-mean-square deviation (RMSD) of 0.351 Å, and the local backbone displacement at position 237 was 0.262 Å (Figure 2). According to UniProt (O15305), Thr237 lies in the last α-helix of the protein (residues 234-245), 11 residues after the predicted second Mg<sup>2+</sup>-binding site (Phe221, Asp223, and Thr226).

![Figure 2](../figures/Figura_2_Report.png)

**Figure 2. Local structure of wild-type and T237M PMM2 at position 237.** Superposition of the wild-type structure (PDB 7O4G, light blue) and the T237M structure (PDB 7O58, yellow), centred on the α-helix that contains residue 237. Residue 237 is highlighted in dark blue in the wild type and in orange in the mutant, and its side chain is shown as sticks: threonine in the wild type and methionine in the mutant, whose longer side chain contains a sulphur atom (yellow stick). The two backbones overlap almost completely in this region (local backbone displacement of 0.262 Å). Image obtained from internal sources.

### Cross-species comparison of gene and protein sequences

The human *PMM2* sequences were compared with those of *Leishmania mexicana* (XM_003874496.1 and XP_003874545.1) and *Vicugna pacos* (XM_072942246.1 and XP_072798347.1). The *V. pacos* record corresponds to a predicted mRNA (transcript variant X7) of 5795 nt, in which only nucleotides 62-742 (681 nt) are coding; the rest are untranslated regions.

At the CDS level, the human sequence was highly similar to that of *V. pacos*, whereas with *L. mexicana* BLASTn aligned only one short region (nucleotides 516-668, which encode residues 172-223) (Table 1). Several nucleotide differences between species did not change the encoded amino acid. For example, codons 2, 3, 4, 12, 13, and 14 differ between human and *V. pacos* but encode the same residues in both species.

At the protein level, similarity with both species extended along almost the whole sequence, including *L. mexicana*, for which the CDS alignment had covered only a small part of the gene (Table 1). The *V. pacos* protein contains a 12-residue insertion after human position 59 and ends after the position equivalent to human residue 213, so it lacks the region corresponding to human residues 214-246.

**Table 1. Pairwise similarity of PMM2 between human and two other species.**

| Species compared with *H. sapiens* | CDS identity | CDS query coverage | Protein identity | Protein positives | Protein query coverage |
| --- | --- | --- | --- | --- | --- |
| *L. mexicana* | 70% | 21% | 57% | 71% | 97% |
| *V. pacos* (isoform X7) | 91% | 62% | 90% | 92% | 87% |

Values were obtained with NCBI BLAST ("Align two or more sequences"), using BLASTn for the CDS and BLASTp for the protein sequences, with the human sequence as query. Identity is the percentage of identical positions in the aligned region; positives also include positions with amino acids of similar properties; query coverage is the percentage of the human sequence included in the alignment. Identity percentages include gap positions.

In the multiple alignment of the three proteins, the N-terminal stretch FDVDGTL (residues 11-17), which contains the DxD motif, was identical in the three species (Figure 3). All the residues annotated as functional in UniProt (O15305) were also identical in *L. mexicana*: the catalytic nucleophile (Asp12), the proton donor/acceptor (Asp14), the residues of the two predicted Mg<sup>2+</sup>-binding sites (Asp12, Asp14, and Asp209; Phe221, Asp223, and Thr226), and the residues that bind mannose 1-phosphate (Arg21, Arg123, Arg134, Arg141, Ser179, and Asp181). In *V. pacos*, all the functional residues present in its sequence were conserved.

Thr237 was identical in *L. mexicana*, and so were several neighbouring positions (Gly228, Ser230, Val231, and Asp236). This position could not be assessed in *V. pacos*, because isoform X7 lacks this region (Figure 3).

![Figure 3](../figures/Figura_3_Report.png)

**Figure 3. Multiple alignment of the PMM2 protein in three species.** Clustal Omega alignment of the PMM2 protein of *L. mexicana* (XP_003874545.1, first row of each block), *H. sapiens* (PMM2_protein_WT, second row), and *V. pacos* (XP_072798347.1, third row). Numbers on the right indicate the position of the last residue of each row in each sequence, and dashes indicate gaps. Symbols below each block indicate identical residues in the three sequences (\*), residues with strongly similar properties (:), and residues with weakly similar properties (.). Green box: FDVDGTL motif. Blue boxes: functional residues annotated in UniProt (O15305), corresponding to the catalytic site, the two Mg<sup>2+</sup>-binding sites, and the mannose 1-phosphate-binding site. Red box: position 237, mutated in the T237M variant.

### Structural comparison between human and *L. mexicana*

The superposition of the human and *L. mexicana* PMM2 structures gave a global RMSD of 1.66 Å, although the two sequences share only 56.4% identity (Figure 4). The largest structural differences were concentrated in one region of the protein, while the rest of the two structures overlapped closely (Figure 4A). The secondary structure was almost identical in the two species, except for the stretch between human residues 65 and 84. At position 237, the local backbone displacement between the two species was 1.465 Å, and the residue was located in an α-helix in both structures.

![Figure 4](../figures/Figura_4_Report.png)

**Figure 4. Structural comparison of human and *L. mexicana* PMM2.** (A) Superposition of the two structures coloured by local backbone displacement: white indicates regions that overlap closely, and increasingly intense red indicates regions that are further apart in space. Yellow segments were excluded from the superposition. (B) The same superposition coloured by species, with the human structure in blue and the *L. mexicana* structure in green. Image obtained from internal sources.