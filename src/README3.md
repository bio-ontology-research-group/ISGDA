# src content
This folder contains:
- Code to prepare a PathDataset (for compatibility with the mOWL library used (https://github.com/bio-ontology-research-group/mowl), you can access its detailed documentation through: (https://mowl.readthedocs.io/en/latest/)
- Code for bma-based GDA scoring: you will need to add your embeddings file, for each gene-disease pair, this codes extracts their relative phenotype embeddings to calculate cosine similarities. It then applies BMA as a reflection for that particular GDA score.
- Code for bma-based GDA scoring: you will need to add your embeddings file, ensuring that genes and disease embeddings exist here.
- Code for metrics, this compares your scores with positives and produces AUC, hits@k, MR, and MRR values.
