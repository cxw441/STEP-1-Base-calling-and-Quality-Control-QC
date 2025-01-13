# STEP 1: Base calling and Quality Control (QC)

Basecaller 
Guppy 
Albacore
Chiron 
Dorado 

wget command

wget https://cdn.oxfordnanoportal.com/software/analysis/dorado-0.8.3-linux-x64.tar.gz

Extraction: tar zxvf dorado-0.8.3-linux-x64.tar.gz



/rds/projects/b/beggsa-clinicalnanopore/wongm/Software/dorado/dorado-0.8.3-linux-x64/bin/dorado basecaller hac /rds/projects/b/beggsa-clinicalnanopore/wongm/Michael_MDM2_150323/Michael_MDM2_150323/20230315_1340_3G_PAG83305_d8f4b46c/pod5_pass/barcode01 > calls_barcode01.bam



module purge

module load bear-apps/2022b/live

module load SAMtools/1.17-GCC-12.2.0

samtools view barcode01.bam | less




https://github.com/wdecoster/nanoQC
 
https://github.com/rrwick/Porechop?tab=readme-ov-file#installation
 






