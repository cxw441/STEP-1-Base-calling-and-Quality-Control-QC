# STEP 1: Base calling and Quality Control (QC)

wget command

wget https://cdn.oxfordnanoportal.com/software/analysis/dorado-0.8.3-linux-x64.tar.gz

Extraction: tar zxvf dorado-0.8.3-linux-x64.tar.gz


/rds/projects/b/beggsa-clinicalnanopore/wongm/Software/dorado/dorado-0.8.3-linux-x64/bin/dorado basecaller hac /rds/projects/b/beggsa-clinicalnanopore/wongm/Michael_MDM2_150323/Michael_MDM2_150323/20230315_1340_3G_PAG83305_d8f4b46c/pod5_pass/barcode01 > calls_barcode01.bam


/rds/projects/b/beggsa-clinicalnanopore/wongm/Software/dorado/dorado-0.8.3-linux-x64/bin/dorado basecaller hac pod5_pass/barcode01 > calls_barcode01.bam


PAG83305_pass_barcode01_d8f4b46c_3cdd3390_0.pod5

/rds/projects/b/beggsa-clinicalnanopore/wongm/Software/dorado/dorado-0.8.3-linux-x64/bin/dorado basecaller hac barcode01/PAG83305_pass_barcode01_d8f4b46c_3cdd3390_0.pod5 > calls.bam


/rds/projects/b/beggsa-clinicalnanopore/wongm/Software/dorado/dorado-0.9.0-linux-x64/bin/dorado basecaller hac /rds/projects/b/beggsa-clinicalnanopore/wongm/Michael_MDM2_150323/Michael_MDM2_150323/20230315_1340_3G_PAG83305_d8f4b46c/pod5_pass/barcode01/ > calls_barcode01.bam







