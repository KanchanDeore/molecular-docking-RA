# 🧪 Molecular Docking in Drug Discovery: Targeting Rheumatoid Arthritis

## 📘 Overview

Welcome! This repository contains a complete project on how **molecular docking** and **bioinformatics tools** are used to discover potential drugs for **Rheumatoid Arthritis (RA)**, an autoimmune disease. It guides you through the **entire pipeline** of drug discovery using **Computer-Aided Drug Design (CADD)**, from understanding the disease to identifying a drug candidate using in silico tools.

This project was completed as part of my M.Sc. in Industrial Biotechnology at B.K. Birla College (Mumbai University) during the academic year 2022–2023.

## 👩‍🔬 About Me

**Kanchan Deore**  
M.Sc. Industrial Biotechnology (2022-2023)  
Mumbai University  
> Passionate about applying computational tools to accelerate drug discovery and improve human health outcomes.

---

## 💡 What is Rheumatoid Arthritis (RA)?

RA is a **chronic autoimmune disease** that causes inflammation in the joints (especially hands, knees, and wrists) and can even affect the lungs, heart, and eyes. It occurs when the immune system mistakenly attacks the body’s own healthy tissues.

Common symptoms include:
- Joint pain, stiffness, and swelling
- Fatigue and weight loss
- Reduced mobility

RA has **no known cure**, but there are drugs that help manage its symptoms and progression.

---

## 🧬 Project Goal

To identify and optimize potential drug candidates that can target proteins involved in RA using **bioinformatics databases** and **molecular docking software** — all done computationally without needing lab equipment.

---

## 🧰 Tools, Software & Databases Used

| Tool | Purpose |
|------|---------|
| **PyRx** | Virtual screening and docking analysis |
| **Chimera** | Protein structure cleaning and visualization |
| **MarvinSketch** | Ligand drawing and modification |
| **UniProt** | Protein sequence and function database |
| **PubChem** | Ligand structures and chemical properties |
| **PDB** | 3D structures of proteins |
| **TTD (Therapeutic Target Database)** | Finding protein targets for diseases |
| **PyMOL** | Converting structures for docking and visualization |

---

## 🧪 Step-by-Step Workflow

### 1. **Disease Selection**
Selected **Rheumatoid Arthritis** due to its autoimmune and systemic nature. Identified it as a target disease that requires safer and more effective drugs.

### 2. **Target Identification**
Using **TTD**, the key protein “**AP2-associated protein kinase 1 (AAK1)**” involved in RA was identified as a suitable therapeutic target.

### 3. **Target Structure Retrieval**
Using **PDB**, the 3D structure of AAK1 (**PDB ID: 5TEO**) was downloaded and cleaned in **Chimera** (removal of water, ligands, etc.) for docking.

### 4. **Ligand Selection**
Potential ligands (drug-like molecules) were retrieved:
- **Baricitinib** – A JAK inhibitor used for RA and COVID-19
- **Niflumic Acid** – Anti-inflammatory compound
- Other analogs retrieved from **PubChem** and modified using **MarvinSketch**

### 5. **Protein-Ligand Docking**
Using **PyRx**, docking was performed between the cleaned target protein and selected ligands. Binding affinity scores were recorded to evaluate how well each molecule binds.

### 6. **Lead Optimization**
Baricitinib and other molecules were modified (functional group editing) to create better analogs. These modified compounds were then redocked to evaluate improved binding.

---

## 📊 Key Results

- **Baricitinib** showed strong binding affinity, confirming its effectiveness.
- Modified analogs showed potential for higher activity and specificity.
- Docking simulations support experimental use and further lab testing.

---

## 📁 Repository Contents

| File | Description |
|------|-------------|
| `kanchan-Molecular_docking_project.docx` | Full original report with diagrams and references |
| `molecular_docking_RA_summary.txt` | Plain text version for quick reference |
| `README.md` | This file – complete guide and explanation |

---

## 🎓 What You’ll Learn From This Project

- Basics of **autoimmune diseases** and drug discovery
- How **virtual screening and docking** works
- Using free **bioinformatics tools and databases**
- Hands-on application of CADD to solve real-world medical problems

---

## 📬 Contact

If you have questions, feel free to connect with me on [LinkedIn](https://www.linkedin.com/) or email me at `deore.k@northeastern.edu`.

---

> 🧠 *This project showcases how science and software come together to create solutions that may one day change lives.*
