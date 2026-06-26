Supplementary Material: Datasets and Data Preprocessing in Machine Learning-Based Insider Threat Detection: A Systematic Literature Review
Authors: Qasim Mohamed Alriyami, Mohd Murtadha Bin Mohamad
Note: this Supplementary material can also be accessed online on GitHub at: https://github.com/alriyami7777-alt/SLR-on-Datasets-and-Data-Preprocessing--Supplement-Alriyami-Murtadha
1. Overview
This repository contains the complete supplementary materials and "audit trail" for our Systematic Literature Review (SLR) titled: " Datasets and Data Preprocessing Techniques for Machine Learning-Based Insider Threat Detection: A Systematic Literature Review."

This review provides a synthesis of (110) primary studies focused on the technical details of multiple datasets and how these datasets and raw security logs are processed and transformed into actionable features for machine learning. The repository ensures full transparency into our methodology, including the search strategy, the PRISMA-2020 selection process, and the specific quality assessment metrics (as an alternative to a risk-of-bias assessment)  used to evaluate data-centric security research.

2. Repository Structure
The repository is organized into six folders:
Folder Name	Primary Content	Format
01_Search_Strategy	Boolean search strings, database search logs, and raw record counts. RIS and CSV files from the databases	PDF
RIS
CSV
02_Study_Selection	PRISMA 2020 flow diagram and the Exclusion Log for the 7 papers excluded during full-text eligibility	PDF / CSV
03_Quality_Assessment	Detailed QA1–QA5 scoring for every paper 	PDF / Excel
04_Data_Extraction	Structured data extraction tables mapped directly to RQ1–RQ4.	PDF
05_Visualizations	Bibliometric data from publication trends and avenues, and keyword frequency visualization.	PDF / Excel
06_PRISMA_Checklists	Completed PRISMA 2020 checklist and PRISMA 2020 checklist for Abstract.	PDF

3. Methodology & Transparency
To ensure the highest level of academic strength, this repository documents two specialized workflows used in our study:
•	AI-Assisted Extraction (Folder 04): We utilized NotebookLM for the initial extraction of technical parameters from the 110 included primary studies.
•	Visualizations (Folder 05): Visualizations were generated through a hybrid pipeline combining qualitative thematic scans (via NotebookLM) and quantitative data synthesis for graphical representation via Google Gemini, Google Colab and MS Excel.  
4. How to Use This Repository
📁 01_Search_Strategy: For Replication & Verification
•	Replicate Searches: Use the provided Boolean strings to run identical queries across WoS, IEEE Xplore, ScienceDirect, ACM, or Scopus.
•	Audit Raw Data: The .ris and .csv files contain the "raw" results before deduplication, allowing you to see exactly what the databases returned on the search date.
📁 02_Study_Selection: For Procedural Transparency
•	Track the Process: The PRISMA 2020 Flow Diagram provides a high-level visual of the inclusion/exclusion phases.
•	Verify Exclusions: It lists the 7 full-text papers that were excluded and provides the specific reasons for their removal.
📁 03_Quality_Assessment: For Rigor Validation
•	Review Scoring: Details on how each of the articles performed against our five Quality Assessment (QA) criteria.
📁 04_Data_Extraction: For Technical Synthesis
•	Answer Research Questions: The structured data is mapped directly to RQ1–RQ4. Use these tables to find specific information on datasets used or data preprocessing techniques.
•	AI Methodology: Review the document on AI-assisted extraction to understand how LLMs were used to accelerate the data synthesis process while maintaining human-in-the-loop accuracy.
📁 05_Visualizations: For Trend Analysis
•	Keyword & Bibliometrics: Use the frequency datasets to identify emerging trends in the literature.
•	Identify Leading Venues: helps identify publication trends and which journals are publishing the most relevant research.
📁 06_PRISMA_Checklists: For Standard Compliance
•	Verify Compliance: These PDFs help find exactly where in our main manuscript we addressed each item required by the PRISMA 2020 reporting standards. 
