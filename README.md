# GDBChEMBL similarity search
## Model identifiers
- Slug: gdbchembl-similarity
- Ersilia ID: eos4b8j
- Tags: Similarity

# Model description
Look for 100 nearest neighbors, according to ECFP4 Tanimoto similarity, in the enumerated GDBChEMBL database.
- Input: SMILES
- Output: Compound (SMILES)
- Model type: 
- Training set: 
- Mode of training: Online

# Source code
- Code: The model uses the web application available at https://gdb-chembl-simsearch.gdb.tools/
- Checkpoints: N/A

# License
The GPL-v3 license applies to all parts of the repository.

# History 
- We have developed a python script that accesses the web server available https://gdb-chembl-simsearch.gdb.tools/ to run the predictions.
- `requests` and `BeautifulSoup` Python libraries are used to post the input to the server and fetch the results. 
- Model was incorporated to Ersilia on 8/15/2022

# About us
The [Ersilia Open Source Initiative](https://ersilia.io) is a Non Profit Organization ([1192266](https://register-of-charities.charitycommission.gov.uk/charity-search/-/charity-details/5170657/full-print)) with the mission is to equip labs, universities and clinics in LMIC with AI/ML tools for infectious disease research.

[Help us](https://www.ersilia.io/donate) achieve our mission or [volunteer](https://www.ersilia.io/volunteer) with us!
