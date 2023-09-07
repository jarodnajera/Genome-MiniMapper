# Genome-MiniMapper
Program that uses a Read Generator and Read Mapper to create a genome mini-mapper

The Read Generator takes in a reference genome in FASTA format, and performs a given N reads composed of a given L length by sampling the genome at random positions. The Read Generator will then create a FASTA file containing the 
reads for the Read Mapper to verify. The Read Mapper will then take in the reference genome and the set of reads created by the Read Generator, and counts how many reads were mapped correctly by comparing them to their original position. The 
Read Mapper keps track of the occurrence of each read through the use of a Suffix Tree
