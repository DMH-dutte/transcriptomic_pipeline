# Transcriptomic pipeline

This is a transcriptomic pipeline written in the workflow manager Snakemake. 

Make sure to exectue each of the pipeline scripts in the correct order:

1. 1st_transcriptomic_pipeline - Quality check\
    Check the quality of your transcriptomes before proceeding. 
2. 2nd_transcriptomic_pipeline - Trimming + 2nd Quality check\
    Adjust the trimming parameters 
3. 3rd_transcriptomic_pipeline - Alignment\ 
    Modify/Delete unnecessary Rules

It is possible to modify parameters or single steps in the pipeline scripts itself. 
Modify the configuration file for applying the pipeline.  
