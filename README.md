# Marijuana Genomes Analysis

This investigates the dataset [here](https://www.kaggle.com/datasets/bigquery/genomics-cannabis/data). 

# Data
My data consists of several huge tables consisting of data about marijuana genomes. It consists of the tables of 
* 'MNPR01_201703' - Consisting of data regarding genome, and proteins
* 'MNPR01_reference_201703',
* 'MNPR01_transcriptome_201703',
* 'cs10_gff',
* 'cs3k_project_info',
* 'cs3k_vcf_cs10_dv090',
* 'sample_info_201703'

# Notebooks

My notebook ```notebooks/data_input.ipynb``` consists of an EDA of this dataset.

My notebook ```notebooks/regression.ipynb``` consists of regression on ```MNPR01_201703```. 

My notebook ```notebooks/neural_net.ipynb``` consists of me building a neural network for this mode.

# Analysis

I shall seek to investigate the relationship between marijuana genomes and proteins. It would make more sense to predict proteins based on genomes

Regression yielded me a test score of 17.9%, which is unsatisfactory. The conclusion I may achieve based on this is that I shall need to try something else. 

Running a CNN model for this dataset yields an error of 0.76, which is pretty good. 
