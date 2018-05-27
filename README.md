# G4-processing
*REQUIREMENTS*
Input Files:
-> Sorted bam files
System requirements:
1) GNU-Awk verison>3.1.5
2) bedtools version>2.26.0
3) samtools version>1.3.1


*ABOUT*
-> This set of codes was used to process bam files and extract regions which were damaged due to IR.
-> The codes have been prefixed by the numerical order in which they are to be used to process the bam files.
-> Note: Do not neglect the "2_control_bam_trim.sh" script as it is necessary for comparison between treated and control samples later.
-> certain stringencies have been hardcoded into the scripts. They are flexible as per the user's requirements.
-> After the "7_filter_damaged.sh" script is run, the user needs to run the "FastaFromBed" command on the resulting bed files to get the nucleotide sequences of the damaged regions which can then be analyzed using any G4 prediction tool like QuadBase or non-B DB.

