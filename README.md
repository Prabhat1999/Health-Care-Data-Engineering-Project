# Health-Care-Data-Engineering-Project

Build an end to end data engineering pipeline, where data from different sources are collected in zones and transformation logic are implemented for the data to be analytically ready in the target.

Below is an architecture of the Data Engineering pipeline, of a heath-care data where the Electronic Medical Record(EMR) data is being the source from Azure SQL Database. NPI ,CPT and ICD codes are extracted from the API and stored in the bronze layer in parquet format. 

(NPI: National Provider Identifier
What it is:
A unique 10-digit number assigned to healthcare providers in the United States.)
(CPT: Current Procedural Terminology
What it is:
A standardized set of 5-digit codes maintained by the American Medical Association (AMA)
Used to describe medical, surgical, diagnostic, and therapeutic services provided to patients)
(ICD: International Classification of Diseases
What it is:
A globally recognized system of codes for diseases, conditions, symptoms, and injuries — maintained by the World Health Organization (WHO).)

Used to identify healthcare professionals and organizations when submitting claims or conducting transactions.
![Screenshot 2025-05-06 152905](https://github.com/user-attachments/assets/47f18d9e-af21-4a8d-a99b-4e0ce4908d15)


