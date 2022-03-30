# GScore:Identifying driver genes in cancer by integrating omics data

## All code downloaded from Releases on the right.

The GScore is used to identify the cancer driver genes.

The GScore is applyied under the R environment.

Install the GScore requied:

1. load  .RData   and GScore.R,

2. run the main_function in GScore.R.
GScore=function(G_mut,mirna_exp,mirna_list,R_mut,mul_edge_list,mul_gene_list)

'mirna_exp' --> A miRNA expression matrix, with rows representing miRNAs and columns representing samples.
'mirna_list' --> For the corresponding relationship between a miRNA and a gene, we select the relationship with high reliability for experimentation, that is, the relationship with the value of 1 in the third column.
'R_mut' --> A gene expression matrix with rows representing genes and columns representing samples including normal samples and cancer samples.
'mul_edge_list' and 'mul_gene_list' are the edges and nodes of the interaction network, respectively.

