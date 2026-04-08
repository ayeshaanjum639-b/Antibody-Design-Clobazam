# 🧬 De Novo Antibody Design Against Clobazam

## 🚀 Project Overview
This project demonstrates a **complete beginner-friendly bioinformatics pipeline** for designing a *theoretical antibody* against a small molecule drug (**Clobazam**) and evaluating its binding using molecular docking.

The workflow is implemented entirely in **Python using Google Colab**, with zero local setup and minimal dependencies.

---

## 🎯 Objectives
- Design antibody variable regions (**VH & VL**)
- Introduce simple **CDR mutations** (de novo concept)
- Prepare ligand and receptor structures
- Perform **molecular docking** using AutoDock Vina
- Visualize binding interactions
- Compare results with a control protein

---

## 🧪 Methodology

### 1. Antibody Design
- Used a known antibody scaffold
- Modified **CDR region** to simulate binding potential

### 2. Ligand Preparation
- Small molecule: **Clobazam**
- Structure obtained from public database
- Converted to docking format (PDBQT)

### 3. Docking
- Tool: **AutoDock Vina**
- Performed:
  - Antibody–ligand docking
  - Control protein–ligand docking

### 4. Visualization
- 3D visualization using **py3Dmol**
- Binding poses analyzed

---

## 📊 Results

### 🔹 Docking Score Comparison

| System            | Binding Energy (kcal/mol) |
|------------------|--------------------------|
| Antibody         | ~ 0.0 (weak binding)     |
| Control Protein  | ~ -4.0 (stronger binding)|

---

## 🖼️ Visual Results

### 📈 Docking Score Plot
![Docking Plot](images/docking_plot.png)

### 🧬 3D Binding Visualization
![3D Visualization](images/visualization.png)

---

## 🧠 Scientific Interpretation

- Antibodies are typically optimized for **large biological antigens**
- Small molecules like drugs require a **well-defined binding pocket**
- The designed antibody lacks such a pocket → **weak binding observed**
- Control protein provides a binding cavity → **better docking score**

👉 This validates both:
- The computational pipeline
- The biological limitation

---

## 🛠️ Tools & Technologies

- Python (Google Colab)
- AutoDock Vina
- Open Babel
- py3Dmol
- Biopython
- Matplotlib

---

## 💼 Applications

- Antibody design (concept level)
- Drug-binding analysis
- Bioinformatics portfolio project
- Educational demonstration

---

## ⚠️ Disclaimer

This is a **computational prototype**.  
Results do not guarantee real-world binding and require experimental validation.

---

## 👤 Author

**Your Name**

---

## ⭐ If you found this useful

Give this repo a ⭐ on GitHub!
