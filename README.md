# genemerge

Given a set of genes, GeneMerge provides statistical rank scores for over-representation
of gene attributes in the set and returns functional or categorical descriptions associated
with each gene. It answers the question, “Is there functional or categorical 'enrichment' of
some kind among this set of genes?” A common use for GeneMerge is the analysis of
microarray and RNA-seq data.

GeneMerge uses the hypergeometric distribution to calculate the over-representation of
gene attributes and provides Bonferroni and False Discovery Rate (FDR) correction for
multiple tests. Output is a tab delimited text file and HTML.

http://www.genemerge.net
