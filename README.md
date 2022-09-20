# 2-Domain_proteins_data

### This repository contains metadata tables and reference trees used in research paper "EFFICIENCY OF  ALIGNMENT FILTRATION FOR PHYLOGENETIC RECONSTRUCTION OF TWO-DOMAIN PROTEINS"

##### Each table (in .tsv format) contains records of proteins for specific taxonomic group and consists of the following columns:
* <b>prot</b> - Uniprot id 
* <b>sp</b> - specie mnemonic
* <b>pf1</b> - Pfam id of first domain in protein
* <b>pf2</b> - Pfam id of second domain in protein
* <b>start_1</b> - start position of first domain in protein sequence (1-based indexing)
* <b>end_1</b> - end position of first domain in protein sequence (1-based indexing)
* <b>start_2</b> - start position of second domain in protein sequence (1-based indexing)
* <b>end_2</b> - end position of second domain in protein sequence (1-based indexing)
* <b>spacer_len</b> - length of the spacer between two domains in protein sequence
* <b>prot_len</b> - length of full protein sequence

For each table, index values represent combinations of columns "pf1" and "pf2"; proteins grouped by unique values in index form orthologous groups.

##### Reference trees were taken from NCBI Taxonomy database as a restriction on the given taxa and converted into Newick format


##### Full version of figure 2 from text: Distribution densities of the proportion of distances between sequences appear to be greater in the case of using most of the protein sequences

<img src="https://github.com/belozersky321/2-Domain_proteins_data/blob/main/kde_1.png">
