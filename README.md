# cluster-counting
The notebooks for counting the number of  C2H2 domain clusters of different size in C2H2 proteins (cluster_counting) and for analyzing the presence of conserved linkers between C2H2 domains (C2H2_linker_counting). It also counts total number of clusters in proteome, median number of C2H2 domains per protein and median cluster size. The linker counting notebook performs search of the presence of conserved motif TGEKP within linkers between C2H2 domains, counts the mean ratio of presence of these linkers within clusters of different size.
Notebooks are written to take as inputs iTOL-formatted .txt files from SMART database (http://smart.embl.de/smart/complete_tree.cgi?ID=ZnF_C2H2) and tsv-formatted files from InterPro/Uniprot database (https://www.ebi.ac.uk/interpro/entry/InterPro/IPR013087/taxonomy/uniprot/#table). Linker counting also requires the presence of associated .fasta files with the same filenames as iTOL/tsv files.
Can be adapted to count any other clusters of protein domains.
# References
Bonchuk AN, Balagurov KI, Baradaran R, Boyko KM, Sluchanko NN, Khrustaleva AM, Burtseva AD, Arkova OV, Khalisova KK, Popov VO, Naschberger A, Georgiev PG. The Arthropoda-specific Tramtrack group BTB protein domains use previously unknown interface to form hexamers. Elife. 2024 Sep 2;13:e96832. doi: 10.7554/eLife.96832. 

Bonchuk AN, Georgiev PG. C2H2 proteins: Evolutionary aspects of domain architecture and diversification. Bioessays. 2024 Aug;46(8):e2400052. doi: 10.1002/bies.202400052.
