# Audit Projects

## 1. Name duplication
This project addresses a high-cost operational failure mode common to any system where human operators create new profiles: duplicate person records that evade detection because they are assigned distinct IDs at entry. Left unresolved for weeks or months, these duplicates cause depending on industry either fragmented patient histories in healthcare, double-sold pipeline in marketing/sales and compliance gaps in financial services. 
The pipeline implements a three-stage resolution strategy — exact match, name-token permutation, and fuzzy similarity based on distance — designed to catch the three most common real-world failure patterns: data entry errors, cultural name-order differences, and cross-language transliteration variants.

## Tools used:
- Jupyter Lab notebooks
- NumPy, Pandas, Re, FuzzyWuzzy, Faker
