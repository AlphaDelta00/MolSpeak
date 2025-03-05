# MolSpeak
I want to *try* to build a model that can predict drug-target interactions by analysing biomedical literature and protein sequences. Maybe one day some researcher can use it to identify new drug candidates or repurpose existing drugs for new targets.

# Day 1
## Workflow? 
I think the best way to do this goes like...
### step 1: collect and prepare data
I am gonna need two sources of data
1. Drug-Target Interaction Data (likely tabular & sequence data) from open source databases.
Potential databases found are:
    - **DrugBank** ([https://www.drugbank.ca/](https://www.drugbank.ca/))
    - **BindingDB** ([https://www.bindingdb.org/](https://www.bindingdb.org/))
    - **ChEMBL** (https://www.ebi.ac.uk/chembl/)
The idea is to extract drug names, target proteins, target sequences and binding affinities

