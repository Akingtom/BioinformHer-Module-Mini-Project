Tracking the Evolution of the Hemoglobin Beta (HBB) Gene across Species
Overview
This repository contains the files, data, and analyses for tracking the evolutionary conservation of the Hemoglobin Beta (HBB) gene across various vertebrate species. The project investigates sequence conservation patterns, constructs phylogenetic relationships, and visualizes conserved amino acid patterns in this essential oxygen transport protein.
Background
Hemoglobin is a tetrameric protein responsible for oxygen transport in vertebrates, comprising two alpha (HBA) and two beta (HBB) globin subunits. The HBB protein contains a heme group that directly binds oxygen, with its functionality influenced by factors such as pH, carbon dioxide concentration, and allosteric effectors. Mutations in the HBB gene are associated with various hemoglobinopathies, including sickle cell disease and beta-thalassemia, highlighting the clinical significance of understanding evolutionary conservation patterns across species.
Research Objectives

Characterize the sequence conservation of HBB across diverse vertebrate species
Visualize conserved amino acid patterns using sequence logos
Infer phylogenetic relationships among selected species based on HBB protein sequences
Compare the derived phylogeny to accepted species relationships

Species Analyzed

Human (Homo sapiens, NP_000509.1)
Chimpanzee (Pan troglodytes, XP_508242.1)
Mouse (Mus musculus, NP_001265090.1)
Cow (Bos taurus, NP_776342.1)
Chicken (Gallus gallus, NP_990820.1)
Zebrafish (Danio rerio, NP_001003431.2)

Methods

Sequence Retrieval: NCBI database using human sequence as query
Pairwise Alignments: NCBI's BLAST Pairwise Alignment tool
Multiple Sequence Alignment: CLUSTAL O (1.2.4)
Sequence Logo Generation: Skylign web server
Phylogenetic Analysis: MEGA X with Neighbor-Joining method and JTT amino acid substitution model

Key Findings

Identified highly conserved motifs critical for heme binding and oxygen coordination
Demonstrated bimodal distribution of conservation scores reflecting different selective pressures
Constructed phylogenetic tree largely recapitulating accepted vertebrate relationships
Found strong correlation between evolutionary conservation and disease-causing mutations

Repository Contents

data/: Raw sequence files and alignment outputs
scripts/: Analysis scripts for MSA and phylogenetic reconstruction
results/: Generated tables, figures, and final alignments
docs/: Project documentation and methodology details

How to Use

Clone this repository

git clone https://github.com/yourusername/hbb-evolution.git

Navigate to the project directory

cd hbb-evolution

Install required dependencies

pip install -r requirements.txt

Run analyses (see individual script documentation)

