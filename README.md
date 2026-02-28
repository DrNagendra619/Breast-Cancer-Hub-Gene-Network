# Breast-Cancer-Hub-Gene-Network
"Protein-Protein Interaction (PPI) network analysis identifying top hub genes (ESR1, FN1, TOP2A) in breast cancer using Cytoscape."
# Breast Cancer Hub Gene Network Analysis

## 📌 Project Overview
This repository contains the data files and network visualizations for a Protein-Protein Interaction (PPI) network analysis. The primary focus of this project is the identification of key hub genes driving biological pathways in breast cancer. This repository serves as the supplementary data repository for an upcoming research paper targeting journal publication.

By mapping these interactions and analyzing the network topology, we identified the most highly connected nodes (hub genes) which may serve as critical biomarkers or potential therapeutic targets.

## 📂 Files in this Repository

* **`string_interactions_short.tsv.sif`**: The complete Simple Interaction Format (SIF) file containing the full list of protein-protein interactions analyzed in this study.
* **`string_interactions_short.tsv.sif_Degree_top10.sif`**: A filtered SIF file containing the interaction subnetwork of the top 10 hub genes isolated by their degree centrality score.
* **`string_interactions_short.tsv.sif_Degree_top10.png`**: A Cytoscape-generated visual representation of the top 10 hub gene subnetwork. Nodes are sized and colored based on their degree and connectivity.

## 🔬 Key Findings & Top Hub Genes

Based on degree centrality within the Cytoscape network, the following targets emerged as the top 10 most highly interconnected hub genes within this subset:

* **ESR1** (Estrogen Receptor 1) 
* **FN1** (Fibronectin 1) 
* **TOP2A** (DNA Topoisomerase II Alpha) 
* **ASPM** * **MELK** * **NCAPG** * **RRM2** * **NEK2** * **KIF4A** * **TPX2** These nodes exhibit the highest number of direct interactions, particularly among heavily researched targets like ESR1 and TOP2A, indicating their central role in the studied network topology.

## 🛠️ Tools & Technologies Used
* **Cytoscape**: For network visualization, topological analysis, and hub gene identification.
* **STRING Database**: For retrieving initial protein-protein interaction data.

## 👨‍🔬 Author
**Nagendra**
* GitHub: [@DrNagendra619](https://github.com/DrNagendra619)

---
*Note: This repository is part of an ongoing industrial-scale research initiative.*
