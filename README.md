# CIF_stat

Name:
    cif_cov_stat.pl
Description:

Usage:
    perl cif_cov_stat.pl <list> <ref> <AA> <out> <out2> <out3>
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
