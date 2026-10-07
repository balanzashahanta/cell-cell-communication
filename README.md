# Cell-to-Cell Communication

## Biological Question

How can a pancreatic alpha cell communicate with a distant target cell to regulate glucose homeostasis?

## Chosen Sender Cell

**Sender cell:** Pancreatic alpha cell

**Biological context:** Pancreatic alpha cells are endocrine cells of the pancreatic islets that respond to low blood glucose by releasing glucagon.

## Signaling Molecule

**Candidate signaling molecule:** Glucagon

**Official gene:** GCG

**Signaling type:** Endocrine

Human Protein Atlas evidence shows GCG/glucagon expression associated with pancreatic islet cells, including pancreatic alpha cells, and indicates that the protein is secreted to blood.

![GCG sender-cell evidence](figures/01_sender_cell_evidence.png)

## Receptor and Receiver Cell

**Ligand:** Glucagon (GCG)

**Receptor:** Glucagon receptor (GCGR)

**Receiver cell:** Hepatocyte

**Signaling context:** Blood glucose regulation and glucose homeostasis

OmniPath shows an interaction from GCG to GCGR, supporting GCGR as a candidate receptor for glucagon.

The Human Protein Atlas shows GCGR as tissue enriched in the liver and associated with hepatocytes, supporting hepatocytes as a biologically reasonable receiver cell.

### Part C Checkpoint

The pancreatic alpha cell produces glucagon, which can signal through the glucagon receptor (GCGR) on hepatocytes in the context of blood glucose regulation and glucose homeostasis.

![OmniPath GCG-GCGR evidence](figures/02_omnipath_evidence.png)

## STRING Network Interpretation

A STRING protein-association network was generated using Homo sapiens with GCGR (glucagon receptor) as the starting receptor. The network contained approximately 12 proteins, including GCG, GNB1, GNB2, GNB3, GNB4, GNB5, GNAS, GNAQ, and GNG13.

The network shows functional associations between GCGR and several G-protein-related proteins. These proteins may help connect receptor activation to downstream cellular responses. However, STRING edges represent functional associations and do not necessarily indicate direct physical binding or a confirmed linear signaling pathway.

![STRING network](figures/03_string_network.png)

### Functional Enrichment

A relevant enriched pathway was **Reactome – Glucagon-type ligand receptors** (10 of 33 proteins; strength = 2.73; FDR = 2.14 × 10⁻²³).

Another relevant pathway was **Reactome – Glucagon signaling in metabolic regulation** (9 of 33 proteins; strength = 2.65; FDR = 1.64 × 10⁻²⁰).

## Experimentally Supported Interaction

*To be investigated using IntAct.*

## Final Cell-to-Cell Communication Model

*To be completed after the database analyses.*

## References and Database Links

- Human Protein Atlas
- OmniPath
- STRING
- IntAct
