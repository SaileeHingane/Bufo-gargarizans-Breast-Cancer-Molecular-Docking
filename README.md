# Bufo-gargarizans-Breast-Cancer-Molecular-Docking
Network pharmacology and molecular docking analysis of Bufo gargarizans bioactive compounds to identify potential therapeutic targets for breast cancer

# In Silico Evaluation of Bioactive Compounds from *Bufo gargarizans* Against Breast Cancer 

## Overview

This project investigates the potential therapeutic activity of bioactive compounds derived from *Bufo gargarizans* against breast cancer using an integrated network pharmacology and molecular docking approach.

Sixteen bioactive compounds were evaluated based on ADME properties, drug-likeness, and predicted toxicity. Resibufogenin was selected as the lead compound for subsequent target prediction, network pharmacology, pathway enrichment, and molecular docking analyses.

## Workflow

Bioactive Compound Collection → ADME and Toxicity Screening → Target Prediction → Breast Cancer Target Identification → Target Intersection → STRING PPI Network → CytoHubba Hub Gene Analysis → GO/KEGG Enrichment → Molecular Docking

## Tools and Databases

- PubChem
- SwissADME
- MolSoft
- ProTox-II
- OMIM
- GeneCards
- SwissTargetPrediction
- STRING
- Cytoscape and CytoHubba
- DAVID
- KEGG
- RCSB Protein Data Bank
- Discovery Studio
- AutoDockTools

## Key Results

PPI network analysis and CytoHubba identified ten hub genes: **LCK, JAK1, JUN, MTOR, HDAC1, BSG, PTPN22, CSK, PIK3CD, and EMB**.

Among these, **LCK, JAK1, MTOR, and PIK3CD** were identified as predicted targets associated with Resibufogenin and selected for molecular docking.

| Target | PDB ID | Best Binding Energy (kcal/mol) | Predicted Ki |
|--------|--------|-------------------------------:|-------------:|
| PIK3CD | 6PYR | -13.53 | 0.12 nM |
| LCK | 2OFV | -12.41 | 0.80 nM |
| JAK1 | 6GGH | -11.58 | 3.25 nM |
| MTOR | 7PED | -11.44 | 4.12 nM |

Among the four evaluated targets, PIK3CD showed the most favorable predicted binding energy with Resibufogenin.

## Repository Structure

- `data/` – Compound screening, target prediction, disease-associated genes, PPI network, hub gene, and pathway analysis data.
- `figures/` – Venn diagram, CytoHubba network, and molecular docking results.
- `manuscript/` – Detailed methodology, results, interpretation, and discussion.

## Conclusion

The integrated network pharmacology and molecular docking analysis identified Resibufogenin as a candidate bioactive compound with predicted interactions involving LCK, JAK1, MTOR, and PIK3CD. Molecular docking indicated the most favorable predicted interaction with PIK3CD.

These findings are based on computational predictions and require experimental validation to confirm their biological and therapeutic significance.

## Authors

**Sailee Hingane**  
