# 
# 🧬 Amino Acid Sequence Analysis & Visualization Dashboard

## 📌 Project Objective
This project aims to analyze protein sequences in FASTA format to extract amino acid frequencies and identify patterns such as the dominance of hydrophilic or hydrophobic residues. The output is visualized using an interactive Power BI dashboard.

---

## 🧪 What the Colab Notebook Does
The Google Colab notebook:
- Parses protein sequences from FASTA files.
- Calculates the frequency of each amino acid.
- Classifies them into **Hydrophilic**, **Hydrophobic**, and **Neutral** groups.
- Exports the results as a CSV (`amino_acid_counts.csv`) for visualization.

Notebook File: `notebook/amino_acid_analysis.ipynb`

---

## 📊 Dashboard Insights (Power BI)
The Power BI `.pbix` dashboard offers:
- A **bar chart** of amino acid frequencies.
- A **pie chart** showing distribution by chemical property.
- A **summary box** highlighting:
  - Dominance of hydrophilic amino acids.
  - Low presence of hydrophobic residues.
  - Sequence balance by functional group.
  
Dashboard File: `dashboard/amino_acid_dashboard.pbix`

---

## 💻 How to Run or Reproduce the Analysis

### Step 1: Run the Notebook
1. Open the Colab notebook:  
   `notebook/amino_acid_analysis.ipynb`
2. Upload your FASTA file or use an existing one.
3. Execute all cells.
4. A CSV file (`amino_acid_counts.csv`) will be generated.

### Step 2: Open the Dashboard
1. Open Power BI Desktop (free download from Microsoft).
2. Open the file:  
   `dashboard/amino_acid_dashboard.pbix`
3. If needed, refresh the data to load your latest CSV.

---

## 📁 Project Structure

