# Data Quality Checks in Python (Demo)

**Tools:** Python (pandas, numpy)

This project replicates data cleaning and validation work typically done in actuarial consulting.  
A synthetic dataset (~4500+ rows) of insurance policies was created, with realistic issues such as missing values, duplicate IDs, and inconsistent dates.

**Notebook steps include:**
- Schema validation (checking required columns exist)
- Missingness checks and handling
- Duplicate detection (by Policy ID / Claim ID)
- Date parsing in `dd/mm/yyyy` format (with validation)
- Range checks for numeric fields (e.g., Premium > 0, ClaimAmount not excessive)
- Business rule checks (e.g., PolicyStartDate ≥ DOB + 18 years, Claim ≤ 5 × Premium)

**Deliverables:**
- `Python_Data_Checks.ipynb` — Jupyter Notebook with code + outputs
- `Python_Data_Checks.html` — Exported version for easy viewing
- `raw_data.csv` — Anonymised input data
- `Python_Data_Checks.xlsx` — Final output generated after checks

⚠️ Note: This demo uses anonymised data. Original datasets used in internships are confidential.

