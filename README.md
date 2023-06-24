# IntegraConnect Oncology Demo
The IntegraConnect oncology Demo database in the Snowflake Marketplace is made up of data from 1019 Lung Cancer and 1018 Breast Cancer Patients. This database has realistic synthetic values of patient data including diagnostic codes, measurements from labs, drugs, visits, costs, procedures, and demographics.

The database is designed to recreate the patient journey for two of the most common types of cancer. It is available without restriction, and it includes many of the fields what are typically included in a de-identified dataset available to partners for research and analysis. It contains a very realistic timeline of events on the patient journey which can be a very useful dataset for people who would like to experiment and learn how to use analytics with oncology data.

There is a **_[data dictionary](Integra_Connect_Demo_Data_DictionaryV4.csv)_** accompanying the database which has a list of tables and columns with descriptions of the fields being used.

There are many terms and codes used in the database too numerous to list here but, for the uninitiated, there are Diagnostic Codes in ICD-9 and ICD-10. Some of the more common codes in IC-10 are C50 for Breast Cancer and C34 for Lung Cancer. Additional sources of information on codes in the dataset are listed below.



### The database is in an OMOP format with 8 tables including: 

  -person
  
  -cost
  
  -measurement
  
  -drug_exposure
  
  -provider
  
  -condition_occurrence
  
  -procedure_occurrence
  
  -visit_occurrence

### Some examples of columns in the dataset include:

  -person_id
  
  -provider_if
  
  -condition_description
  
  -drug_source_value
  
  -total_charge
  
  -total_paid
  
  -visit_source_value
  
  -procedure_source_value
  
  -drug_concept_id
  
  -procedure_source_code_name
  
  -measurement_concept_id



Additional sources of information on OMOP, the dataset, and codes used include

https://www.ohdsi.org/data-standardization/

https://athena.ohdsi.org/search-terms/start

https://www.ama-assn.org/practice-management/cpt/cpt-overview-and-code-approval

https://www.aapc.com/codes/cpt-codes-range/

https://loinc.org/

https://www.fda.gov/drugs/drug-approvals-and-databases/national-drug-code-directory

https://www.nlm.nih.gov/research/umls/rxnorm/index.html
