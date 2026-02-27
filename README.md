BiomarkerMine

Project by Ryan Tso, Jared Crocco and Laud Randy Amofah as part of the BenchSpark Hackathon powered by Google Cloud

Problem Statement

Over 90% of oncology clinical trials now require companion biomarkers, yet finding reliable tissue-specific biomarkers remains a major bottleneck in drug development. Poor patient stratification leads to failed trials costing billions and delays potentially life-saving treatments. 
 
Current Solution 

Take the input of a disease or tissue from the user, search through the Genotype Tissue Expression (GTEx) for genes that were very specific to that specific tissue, and had a high expression rate. We calculated a tau score that measures gene expression specificity, it ranges from 0 to 1 where 1 is highly specific to a certain tissue and 0 is broadly expressed in all tissue. We used Transcripts per Million (TPM) to determine the expression levels, and set a threshold of >0.85 tau and >1500 TPM to determine the top 5 biomarker candidates. The current solution was only tested for prostate or prostate cancer as an input, we wanted a proof of concept before we employed a solution for any input.  

Future Solutions

Employ more databases to the pipeline to provide more relevant information on the top candidate biomarkers. The ClinVar database can help determine if variants of the biomarkers are linked to cancer. The Human Protein atlas database can also be referenced for a protein-level validation for the biomarkers. 


Tools Used

ChatGPT, Gemini, and Claude 
