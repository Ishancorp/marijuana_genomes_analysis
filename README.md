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

My notebook ```notebooks/regression.ipynb``` consists of regression on ```MNPR01_201703```. Regression yielded me a test score of 17.6%, which is unsatisfactory. The conclusion I may achieve based on this is that I shall need to try something else. 

My notebook ```notebooks/neural net.ipynb``` consists of me building a neural network for this mode.
