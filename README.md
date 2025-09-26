# **Realistic Drugs & Their Side Effects Analysis - A Machine Learning Approach**
An end-to-end real-time project on pharmaceutical data, focused on exploring statistical modeling, hypothesis testing, machine learning, and business intelligence techniques.

## About Dataset

> This comprehensive pharmaceutical synthetic dataset contains **1,393 records** of synthetic drug information with **15 columns**

source : [Kaggle/datasets](https://www.kaggle.com/datasets/pratyushpuri/drug-labels-and-side-effects-dataset-1400-records/data)

 
 `realistic_drug_labels_side_effects.csv`
 
|Data Types | Domain  |Use Case |
|----------|------------|---|	
|Mixed (intentional for data cleaning practice)|Pharmaceutical/Healthcare|	ML Training, Data Analysis, Healthcare Research|

### Column Specifications

> Categorical Features

|Column Name	|Data Type	|Unique Values	|Description	|Example Values|
|------------|-----------|----------|-----------|----------|
|`drug_name`	|Object|	1,283 unique|	Pharmaceutical drug names with realistic naming patterns	|"Loxozepam32", "Amoxparin43", "Virazepam10"|
|`manufacturer`|	Object|	10 unique	|Major pharmaceutical companies	|Pfizer Inc., AstraZeneca, Johnson & Johnson|
|`drug_class`	|Object	|10 unique	|Therapeutic drug classifications|	Antibiotic, Analgesic, Antidepressant, Vaccine|
|`indications`	|Object|	10 unique	|Medical conditions the drug treats|	"Pain relief", "Bacterial infections", "Depression treatment"|
|`side_effects`|	Object|	434 unique|	Combination of side effects (1-3 per drug)|	"Nausea, Dizziness", "Headache, Fatigue, Rash"|
|`administration_route`|	Object	|7 unique|	Method of drug delivery|	Oral, Intravenous, Topical, Inhalation, Sublingual|
|`contraindications`|	Object	|10 unique	|Medical warnings for drug usage|	"Pregnancy", "Heart disease", "Liver disease"|
|`warnings`|	Object	|10 unique|	Safety instructions and precautions	|"Take with food", "Avoid alcohol", "Monitor blood pressure"|
|`batch_number`|	Object|	1,393 unique|	Manufacturing batch identifiers|	"xr691zv", "Ye266vU", "Rm082yX"|
|`expiry_date`|	Object	|782 unique|	Drug expiration dates| (YYYY-MM-DD)	"2025-12-13", "2027-03-09", "2026-10-06"|
|`side_effect_severity`|	Object|	3 unique	|Severity classification|	Mild, Moderate, Severe|
|`approval_status`|	Object|	3 unique	|Regulatory approval status|	Approved, Pending, Rejected|

 > Numerical Features

|Column Name	|Data Type|	Range	|Mean|	Std Dev|	Description|
|------------|-----------|----------|-----------|----------|---|
|`approval_year`|	Float/String*|	1990-2024|	2006.7|	10.0|	FDA/regulatory approval year|
|`dosage_mg`	|Float/String*	|10-990 mg|	499.7	|290.0|	Medication strength in milligrams|
|`price_usd`|	Float/String*	|$2.32-$499.24|	$251.12|	$144.81|	Drug price in US dollars|

**Key statistics :**
- Manufacturer Distribution
  
   |Manufacturer	|Count|	Percentage|
   |--------------|----|--|
   |Pfizer Inc.|	170|	12.2%|
   |AstraZeneca|	~140|	~10.0%|
   |Merck & Co.|	~140	|~10.0%|
   |Johnson & Johnson	|~140	|~10.0%|
   |GlaxoSmithKline	|~140|	~10.0%|
   |Others|	~623	|~44.8%|

- Drug Class Distribution
  
   |Drug Class	|Count	|Most Common|
   |-------|--|--|
   |Anti-inflammatory	|154	|✓|
   |Antibiotic	|~140	||
   |Antidepressant|	~140	||
   |Antiviral|	~140	||
   |Vaccine|	~140	||
   |Others|	~679||	

- Side Effect Severity
  
   |Severity|	Count|	Percentage|
   |----------|---|---|
   |Severe	|488	|35.0%|
   |Moderate	|~453|	~32.5%|
   |Mild|	~452	|~32.5%|
-------------------------------------------------------------
### Potential Use Cases
1. Machine Learning Applications
   
   - Drug Approval Prediction: Predict approval likelihood based on drug characteristics
   - Price Prediction: Estimate drug pricing using features like class, manufacturer, dosage
   - Side Effect Classification: Classify severity based on drug properties
   - Market Success Analysis: Analyze factors contributing to drug market performance

2. Data Engineering Projects
   - ETL Pipeline Development: Practice data cleaning and transformation
   - Data Quality Assessment: Implement data validation and quality checks
   - Database Design: Create normalized pharmaceutical database schema
   - Real-time Processing: Stream processing for drug monitoring systems

3. Business Intelligence
   - Pharmaceutical Market Analysis: Manufacturer market share and competitive analysis
   - Drug Safety Analytics: Side effect patterns and safety profile analysis
   - Regulatory Compliance: Approval trends and regulatory timeline analysis
   - Pricing Strategy: Competitive pricing analysis across drug classes

**Next Steps:**
   1. **Data Cleaning Pipeline:** Implement comprehensive data preprocessing
   2. **Feature Engineering:** Create derived features for enhanced analysis
   3. **Statistical Analysis:** Perform correlation analysis and hypothesis testing
   4. **Machine Learning Models:** Build predictive models for various use cases
   5. **Visualization Dashboard:** Create interactive dashboards for insights
   6. **Documentation:** Maintain detailed data lineage and methodology docs

----------------------------------------------------------------------------------
## **Author**
### Erukonda Saikiran
 | Aspiring Data scientist | Python, ML Algorithms, SQL, PostgreSQL, Power BI |   [My LinkedIn](https://www.linkedin.com/in/saikiran-erukonda-4379911a3/) 
 
 "Learn and Apply to create something New!" is my motto
