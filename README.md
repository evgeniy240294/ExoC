# ExoC

# Run bwa-mem
'''
    time bwa mem -t 14 /mnt/storage/home/eamozheiko/bwa_index/hg19.fa.gz s${SAMPLE}_R1.fastq.gz s${SAMPLE}_R2.fastq.gz > s${SAMPLE}.sam
'''


# Run sam_to_valid_pairs.sh
'''
    ./sam_to_valid_pairs.sh sam_file out_dir
'''


