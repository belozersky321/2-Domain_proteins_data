# 2-Domain_proteins_data

### This repository contains metadata tables used in research paper "EFFICIENCY OF  ALIGNMENT FILTRATION FOR PHYLOGENETIC RECONSTRUCTION OF TWO-DOMAIN PROTEINS"

Each table contains records of proteins for specific taxonomic group and consists of the following columns:
* <b>prot</b> - Uniprot id 
* <b>sp</b> - specie mnemonic
* <b>prot_sp</b> - Uniprot id and specie mnemonic merged with an underscore
* <b>pf1</b> - Pfam id of first domain in protein
* <b>pf2</b> - Pfam id of second domain in protein
* <b>pf12</b> - Pfam ids of first and second domains merged with an underscore
* <b>sp_pf12</b> - previous column with added specie mnemonic
* <b>start_1</b> - start position of first domain in protein sequence (1-based indexing)
* <b>end_1</b> - end position of first domain in protein sequence (1-based indexing)
* <b>start_2</b> - start position of second domain in protein sequence (1-based indexing)
* <b>end_2</b> - end position of second domain in protein sequence (1-based indexing)
* <b>spacer_len</b> - length of the spacer between two domains in protein sequence
* <b>prot_len</b> - length of full protein sequence
