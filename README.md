# CancerLandscapesPreprocessing
This is a repository containing a single jupyter notebook that preprocesses TCGA data for use by gpmap tool from David McCandlish's lab

There are two files that need to be downloaded to use this notebook:

1. Table 1-s2.0-S2211124722010920-mmc2.xlsx that can be downloaded here: https://ars.els-cdn.com/content/image/1-s2.0-S2211124722010920-mmc2.xlsx
2. Table TCGA-CDR-SupplementalTableS1.xlsx that can be downloaded here: https://api.gdc.cancer.gov/data/1b5f413e-a8d1-4d10-92eb-7c4ae739ed81
3. Table mc3.v0.2.8.PUBLIC.maf that can be downloaded here: http://api.gdc.cancer.gov/data/1c8cfe5f-e52d-41ba-94da-f15ea1337efc

One needs to download all of these, create a directory called 'data' inside the repository and put all the tables there. Having done that, one can run the notebook from top to bottom. As as result you will get a table called preprocessed_data_query_genes_by_cancer_type.tsv containing numbers of patients a specific mutation has been obesrved in for each cancer type.
