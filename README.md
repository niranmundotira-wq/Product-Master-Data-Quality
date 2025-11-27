# Product Master Data Quality Improvement Project

This project shows how I work as a Senior Data Steward to improve Product Master Data quality by extracting, profiling, cleansing and validating product information using Databricks and Informatica P360.

---

## 🎯 Objective
Improve quality and reliability of Product Master Data by identifying missing, incorrect and duplicate fields, applying validation rules and publishing accurate golden records to business systems.

---

## 🧑‍💼 My Responsibilities in Product MDM

- Extract product data from internal systems into Databricks
- Perform data profiling to identify missing or incorrect attributes
- Standardize UOM, brand and product names
- Collect missing data from manufacturers’ websites for enrichment
- Load data into Informatica P360 for validation and governance checks
- Apply duplicate detection and golden record creation rules
- Publish validated data to downstream ERP and e-commerce systems

---

## 🔄 Product MDM Workflow I Follow

1️⃣ Extract product information into Databricks. 
2️⃣ Perform profiling to identify data gaps and quality issues  
3️⃣ Standardize & enrich data where needed  
4️⃣ Load updated data into Informatica P360  
5️⃣ Apply validation rules and governance approvals  
6️⃣ Generate golden records using match & merge  
7️⃣ Publish golden data to ERP and e-commerce systems

---

## 🔍 Common Data Quality Issues Found

| Issue Type | Why It Happens | Impact | How I Fix It |
|-----------|----------------|--------|--------------|
| Missing product names | Vendor data gaps | Cannot search product | Manual enrichment |
| Duplicate GTIN | Multiple vendor uploads | Wrong product ordering | Match & merge rules |
| Invalid category mapping | Misclassification | Wrong reports | Domain validation |
| UOM inconsistencies | Different vendor formats | Confusion in quantity | Standardization rules |

---

## 🧹 Data Quality Rules Applied

| Rule Type | Purpose | Example |
|----------|---------|---------|
| Mandatory Field Check | Ensure product is searchable | Product_Name IS NOT NULL |
| Uniqueness Check | Remove duplicate listings | Duplicate GTIN removal |
| Standardization | Ensure consistent formatting | UPPER(TRIM(Product_Name)) |
| Domain Validation | Correct product hierarchy | Category IN (valid list) |

---

## 📈 Business Value

- Improved accuracy and trust in product data across systems  
- Better product search and customer experience in ERP/e-commerce  
- Reduced duplicate entries → less rework for business users  
- Right category mapping → correct analytics and reporting  
- Faster product onboarding for sales and operations  
