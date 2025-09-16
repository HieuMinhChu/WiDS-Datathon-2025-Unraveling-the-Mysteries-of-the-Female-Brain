# WiDS Datathon 2025 – CAP6942 Capstone Project

**Team Project:** *Unraveling the Mysteries of the Female Brain*  
Course: CAP6942 – Capstone Project  
Team Members: Rosali Gonzalez, Hieu Chu, Wen Fong Wang  
Competition: WiDS Datathon 2025 (#WiDSDatathon)

---

## 📖 Project Overview
This project investigates **sex-based differences in adolescent brain development** using **functional MRI (fMRI) connectivity data**.  
We combined neuroscience, data science, and machine learning to analyze how brain connectivity evolves differently across males and females, and how these differences correlate with mental health outcomes.

**Core Research Question:**  
*How do brain networks develop differently across males and females during adolescence?*

---

## 🧠 Key Contributions
- **Focused on female neurodevelopment**, an historically understudied area.  
- **Extracted brain connectivity matrices** from fMRI data and analyzed patterns across sex.  
- **Modeled age prediction** using ML algorithms (Ridge regression, Random Forest, GNNs, Transformers).  
- **Evaluated behavioral impacts**:  
  - Females showed higher early brain connectivity, peaking around ages 9–11.  
  - Males showed slower growth and a lower peak around 10–11.  
  - Females reported more anxiety, while males exhibited more attention/impulsivity issues.  

---

## 🔬 Methodology
We adopted a **CRISP-DM + Agile** hybrid workflow:  

1. **Project Launch** – Defined scope, risks, and dataset structure.  
2. **Data Preparation & EDA** – Processed fMRI connectivity data, cleaned metadata, engineered features, and visualized patterns.  
3. **Model Development** – Applied dimensionality reduction, trained ML & DL models, optimized hyperparameters.  
4. **Validation & Insights** – Cross-validated models, assessed bias/overfitting, and analyzed sex-specific connectivity trends.  
5. **Final Reporting** – Summarized findings in presentation, report, and video.  

---

## 📊 Results & Insights
- **Brain Connectivity Trends**: Declines over adolescence for both sexes, with females showing earlier and stronger peaks.  
- **Predictive Modeling**: Ridge regression achieved the best balance of error and R², offering moderate predictive power.  
- **Sex-Based Differences**:  
  - Strongest difference found between Region 184–185 (+0.0873 for females).  
  - Largest negative difference: Region 131–185 (−0.1151 for females).  

---

## 💡 Lessons Learned
- **Practical Data Science Skills**: Hands-on with CRISP-DM, Agile teamwork, and project risk management.  
- **Data Preparation is Critical**: Preprocessing and normalization were essential to achieving usable results.  
- **Holistic Thinking**: Explored neuroscience, behavioral science, and machine learning perspectives.  

---

## 🚀 Future Directions
- Expand dataset with more balanced age and gender representation.  
- Improve interpretability with **Graph Neural Networks** (better suited for brain network analysis).  
- Collaborate with clinicians to ensure **real-world impact** for ADHD, anxiety, and depression diagnostics.  
- Develop **specialized predictive models** tailored to specific mental health conditions.  

---

## 📜 License
This project is for academic and portfolio purposes only.  
Original dataset and methods are credited to WiDS Datathon 2025 organizers and collaborating institutions.
