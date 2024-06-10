# Population_genetic_MLE
The tool can calculate allele frequency, nucleotide diversity and  Watterson theta from a multisample .bam or set of .bam files.
Usage:
  python3 MLE_phred_Tool scoresfile.py --[flag]  [in1.bam in2.bam ...  or other samtools mpileup input]
    --h - help
    mode flags: 
        --freq - frequency (default)
        --pi - nucleotide diversity
    for samtools mpileup input you may call samtools mpileup --h 

Requirements:
  samtools