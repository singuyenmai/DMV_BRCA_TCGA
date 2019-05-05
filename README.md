# Analyses on TCGA data studying DNA methylation valleys in breast cancer

# Preliminary results
In *preliminary* folder, results from prior analyses on WGBS data are stored. <br/>
These include positions of DMV signatures that are differentially methylated in triple negative and/or in endocrine resistant tumors; and their associated genes.

# Access and query TCGA data on Google BigQuery
## Requirements
- Have a billing enabled Google Cloud Platform (GCP) project
- In the GCP project, BigQuery API is enabled. 
- Authentication is set up.
- Python package `google-cloud-bigquery` is installed. Can be by `conda install -c conda-forge google-cloud-bigquery`

*For detailed instructions: go [here](https://cloud.google.com/bigquery/docs/quickstarts/quickstart-client-libraries#client-libraries-install-python)*

# Remained problems/questions
- Among patients with "Low risk occurrence", are they different in treatment progress, such as different combinations of therapy, hormone therapy as neoadjuvant or adjuvant therapy?

- Same for among patients with "Complete response", did they respond better because they received hormone therapy with different strategy?

- Cam we just compare: ("Low risk occurrence" + "Complete response") vs. ("Occured" + "Progressive/Stable")
