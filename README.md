# Wind Resource Assessment Course

This repository contains training materials for wind resource assessment using Python, PyWAsP, and WAsP.

## 📘 Course Objectives
- Learn fundamentals of wind energy and aerodynamics
- Perform data cleaning and quality control
- Build terrain-aware wind models
- Generate wind atlas and perform micro-siting
- Calculate Annual Energy Production (AEP)
- Validate models and quantify uncertainty

## 📂 Repository Structure
- `lectures/` → Jupyter notebooks with theory + examples
- `assignments/` → Lab exercises (data cleaning, terrain modeling, AEP)
- `data/` → Sample datasets (BWC files, DEMs, turbine specs)
- `docs/` → Supporting documentation

## 🛠️ Requirements
- Python 3.10+
- PyWAsP
- WindKit
- Jupyter Notebook
- QGIS (optional, for terrain modeling)

## 🚀 Getting Started
```bash
git clone https://github.com/<your-username>/wind-resource-assessment-course.git
cd wind-resource-assessment-course
conda env create -f environment.yml
jupyter notebook
