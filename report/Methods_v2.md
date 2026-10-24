## Methods

For the analysis of protein structure and differences, Uniprot record O15305 was used to reference the PMM2 Human WT protein, PDB records 7O1B and 7O58 for the PMM2 Human WT and Mutant proteins respectively.

For the purpose of sequence alignments, FASTA sequences for the Human PMM2 WT and mutant sequences, both CDS and protein, were provided by internal sources and can be found in the supplemental information.

For the orthologs, FASTA files associated to the following NCBI accessions were used: for the Leishmania mexicana CDS XM_003874496 and protein XP_003874545, for the Vicugna Pacos CDS XM_072942246 and protein XM_072942246. All versions 1 of their accessions. These were found by setting the Human PMM2 WT CDS in the Query box of BLASTn, and limiting the search to each of the two species while prioritizing somewhat similar sequences. And by setting the Human PMM2 protein in the Query box of BLASTp, and limiting the search to each of the two species while prioritizing somewhat similar sequences. 

In order to generate the sequence alignments between the Human WT and mutant sequences, the BLAST alignment tool was used. This was done by opening the BLASTn (resp. BLASTp) interface, copying the Human WT CDS (resp. protein) FASTA file into the Query section, ticking the “Align two or more sequences” box and copying the Human Mutant CDS (resp. protein) into the Subject Sequence block, each with its corresponding tag, then BLASTing the query.

So as to analyze the WT vs Mutant sequence alignments, the “Pairwise with dots for alignments” alignment view was chosen. The ___ tool was also used, specifically for the CDS alignment, to locate which codon the mutation was part of.

For the ortholog comparison the first step was to cut the nucleotides before the start codon and after the stop codon from the V.Pacos FASTA file, as it was otherwise about 5000 nucleotides longer than the CDS of the other two species. The alignment itself was done with the Clustal Omega sequence alignment tool (CLUSTAL O(1.2.4) multiple sequence alignment), by selecting the type of sequences compared (first DNA, then proteins), and adding the human sequence, the L.mexicana, the V.Pacos sequences into the “Input sequence” box accompanied by their tags and separated by a newline.

The Clustal Omega sequence alignment tool marks under each aligned set of nucleotides whether the elements of the position are the same (*) or not ( ). For proteins, in the case that the amino acids are different, it also differentiates whether they are from similar (:) or vaguely similar (.) physicochemical groups. These marks were used to differentiate the highly conserved regions from the not-so-conserved regions.

The analysis of the aligned sequences was complemented with a report on the structural alignment of the PMM2 Human WT protein sequence and the L.mexicana protein sequence, provided by internal sources. This report includes statistical data on sequence identity, percentage of proteins with coinciding physicochemical class, Global RMSD, primary and secondary structure alignment, local backbone displacement, and 3D imaging of the two proteins superimposed. It also includes information on the disease-associated variant of the protein, including the protein mutation type and place, local backbone displacement of the variant, global WT-Mutant RMSD and imaging of the WT and mutant proteins superimposed, specifically around the mutated region.

During this project different AI tools were used to format citation of bibliography, adapt our texts to Markdown format, check for orthographical errors, [and more?].


