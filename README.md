# CIF_stat

Name:

    cif_cov_stat.pl
    
Description:

Usage:

    perl cif_cov_stat.pl <list> <ref> <AA> <stat_file> <all_file> <pass_file>
    
Options:

	-L,--list	List of cif.gz file
	
	-R,--ref	A fasta file of spike protein
	
	-A,--AA		The abbreviation of Amino acid
	
	-S,--stat	The result of statistics
	
	-F,--file	The result of all chain
	
	-P,--pass	The result after filer
	
	help		print this help information
	
e.g

	perl cif_cov_stat.pl -L list -R P0DTC2.ref.fasta -A AA.ref.txt -S stat.xls -F all_file.xls -P pass_file.xls

# Introduction

cif_cov_stat.pl is a perl program used to statistics Spike protein. 
	
The statistics file(stat.xls) is filtered by the following two conditions :

	1.The coverage of at least 3 chain in each file exceeds 800 Amino acids；
	
	2.Filter out the file with more than 300 Amino acids inconsistent.

pass_file.xls is the file after filtered by the following two conditions.

all_file.xls is the file of all ID and chains.


