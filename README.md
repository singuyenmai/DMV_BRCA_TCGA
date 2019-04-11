# Analyses on TCGA data studying DNA methylation valleys in breast cancer

# Preliminary results
In *preliminary* folder, results from prior analyses on WGBS data are stored. <br/>
These include positions of DMV signatures that are differentially methylated in triple negative and/or in endocrine resistant tumors; and their associated genes.

# Access and query TCGA data on Google BigQuery
## Requirements
- Have a billing enabled Google Cloud Platform (GCP) project
- In the GCP project, BigQuery API is enabled. [Instructions here](https://console.cloud.google.com/flows/enableapi?apiid=bigquery&_ga=2.28176190.-302260015.1553500890)
- Authentication is set up. Follow instructions in [this page](https://cloud.google.com/bigquery/docs/quickstarts/quickstart-client-libraries#client-libraries-install-python)
- Python package `google-cloud-bigquery` is installed. Can be by `conda install -c conda-forge google-cloud-bigquery`
