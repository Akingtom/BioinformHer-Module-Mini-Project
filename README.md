# 🧬 Tracking the Evolution of the Hemoglobin Beta (HBB) Gene Across Species 🐟🐄🐒

## 📝 Project Description  
This project investigates the evolutionary conservation of the **Hemoglobin Beta (HBB) gene** across vertebrate species. The HBB gene encodes a critical subunit of hemoglobin, the protein responsible for oxygen transport in vertebrates. The study includes:  
- 🧩 Sequence retrieval  
- 🔍 Pairwise and multiple sequence alignments  
- 🌳 Phylogenetic analysis  
- 📊 Visualization of conserved motifs  

## 🔑 Key Findings  
- **🧬 Sequence Conservation**: HBB shows high conservation in functional domains (e.g., heme-binding regions), with decreasing identity as evolutionary distance increases.  
- **✨ Conserved Motifs**: Identified critical motifs (e.g., `YPWTQR`, `HCDKLHVDPENFR`) for heme binding and structural stability.  
- **🌍 Phylogenetic Analysis**: Tree aligns with vertebrate relationships, highlighting strong purifying selection.  
- **🏥 Clinical Relevance**: Pathogenic mutations (e.g., sickle cell disease) often occur at conserved residues.  

## 📂 Files Included  
1. **`HBB_MiniProject_TomilolaAkingbade.pdf`**: Full project report.  
2. **`Figures/`**:  
   - 🖼️ Pairwise alignments (Human vs. Chimpanzee, Human vs. Zebrafish).  
   - 🧬 Multiple sequence alignment (MSA) of HBB proteins.  
   - 📊 Sequence logo showing conservation patterns.  
   - 🌳 Phylogenetic tree of HBB sequences.  

## 🛠️ Tools and Methods  
- **🔎 Sequence Retrieval**: NCBI BLAST (`blastp`) using human HBB (`NP_000509.1`).  
- **📏 Alignments**: NCBI BLAST Pairwise Alignment, **CLUSTAL O** for MSA.  
- **🎨 Visualization**: Skylign for sequence logos.  
- **🌳 Phylogenetics**: **MEGA X** (Neighbor-Joining, JTT model, 1000 bootstraps).  

## 🐾 Species Analyzed  
| Species          | Common Name     | Accession Number     |
|------------------|-----------------|----------------------|
| *Homo sapiens*   | Human           | `NP_000509.1`        |
| *Pan troglodytes*| Chimpanzee      | `XP_508242.1`        |
| *Bos taurus*     | Cow             | `NP_776342.1`        |
| *Mus musculus*   | Mouse           | `NP_001265090.1`     |
| *Gallus gallus*  | Chicken         | `NP_990820.1`        |
| *Danio rerio*    | Zebrafish       | `NP_001003431.2`     |

## 🔄 How to Reproduce  
1. **Download** sequences from NCBI using the provided accession numbers.  
2. **Align**: Use `BLAST` or `Clustal Omega` for pairwise/MSA.  
3. **Visualize**: Upload MSA to **Skylign** for logos.  
4. **Build Tree**: Run **MEGA X** (Settings: Neighbor-Joining, JTT model, 1000 bootstraps).  

## 🚀 Future Directions  
- 🌐 Expand taxonomic sampling (e.g., reptiles, amphibians).  
- 🔄 Analyze the entire globin gene family for duplication events.  
- 🏜️ Investigate lineage-specific adaptations (e.g., high-altitude species).  

## 📬 Contact  
**Tomilola Akingbade**  
📧 victomilola@gmail.com
  

---  
**📜 License**: Open-source under [MIT License](LICENSE).  
**🏷️ Keywords**: `HBB` | `hemoglobin` | `evolution` | `phylogenetics` | `sequence conservation`  
