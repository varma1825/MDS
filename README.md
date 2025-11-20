Below is a polished, professional, GitHub-ready **README description** for your project.
It is clean, clear, and easy for any viewer to understand — perfect for a public repo.

You can paste this directly into a `README.md` file.

---

# ⭐ **README.md — Project Description**

# **Identifying Public Health Risks Through Dietary Purchase Patterns in London Using NHS Eatwell Guide**

This project analyses grocery purchasing behaviour across London using the **Tesco Grocery 1.0 dataset** and compares it to the UK’s national dietary framework — the **NHS Eatwell Guide**. The aim is to identify **public health risks**, highlight **dietary inequalities**, and understand how closely different London wards follow the recommended balanced diet.

---

## 📘 **Project Overview**

Millions of anonymised Tesco transactions are aggregated at the **ward level** (625 London wards). These item-based purchase patterns are then mapped to the six Eatwell Guide food groups:

* Fruit and Vegetables
* Starchy Carbohydrates
* Protein Foods
* Dairy and Alternatives
* Oils and Spreads
* Foods High in Fat, Salt, and Sugar (HFSS)

The dataset is reorganised to calculate **the proportion of items** in each category per ward. These proportions are then compared to the ideal Eatwell Guide proportions to determine how balanced (or imbalanced) purchasing behaviour is at the community level.

---

## 🧮 **Core Methods**

### **1. Eatwell Category Proportions**

For each ward:
[
\text{Proportion}_{g,w} = \frac{\text{Items in group } g}{\text{Total Tesco items in ward } w}
]

### **2. Dietary Difference Score**

A custom metric summarising how different each ward’s food basket is from the Eatwell Guide recommendations.
Lower values = more aligned with a healthy diet
Higher values = greater deviation

### **3. Mapping and Spatial Analysis**

Using R packages such as **sf**, **tmap**, and **ggplot2**, the project visualises:

* Individual category maps (Fruit & Veg, Carbs, Protein, Dairy, Oils, HFSS)
* A final **Dietary Difference Score map** showing overall deviation

---

## 🌍 **Key Findings**

* Most London wards show **moderate to high deviation** from the Eatwell Guide.
* Only a small number of wards have purchasing patterns close to recommended healthy proportions.
* Areas with the highest deviation typically purchase more **sugary drinks, ready-made meals, and sweets**, and fewer **fruit, vegetables, and starchy carbohydrates**.
* Spatial patterns reveal clear **dietary inequalities** across London.

---

## 🛠️ **Technologies Used**

* **R 4.x**
* **R Markdown**
* Packages: `dplyr`, `sf`, `tmap`, `ggplot2`, `readr`, `tidyverse`

---

## 📂 **Repository Contents**

* `/data/` – Tesco Grocery 1.0 dataset (not included in public repo for privacy)
* `/analysis/` – R Markdown scripts
* `/figures/` – Maps and visual outputs
* `/report/` – Final report (PDF)
* `/appendices/` – Supplementary materials

---

## 🎯 **Purpose of the Project**

This project helps identify **public health risks** by highlighting where diets are most unbalanced. Using real purchase behaviour rather than self-reported surveys gives a more accurate picture of:

* Dietary inequalities


