## September 27, 2025

**Planned Work:**  
- Create project folder and documentation structure.  
- Install Power BI Desktop & set up Power BI Service account.  
- Identify required dashboard pages.  

**Work Done:**  
- ✅ Created GitHub repository and added initial folder structure (`data/`, `docs/`, `visuals/`, `pbix/`).  
- ✅ Installed **Power BI Desktop** on local machine.  
- ✅ Drafted initial documentation file `ProjectBrief.md`.  
- ✅ Decided on 5 dashboard pages:  
  1. **Overview Dashboard** – summary of elections, parties, seat share.  
  2. **Geographical Map Dashboard** – state/constituency-wise results.  
  3. **Trends Dashboard** – vote share trends, turnout, past vs current comparisons.  
  4. **Candidate Dashboard** – individual candidate profiles, performance, margins.  
  5. **Media Dashboard** – simplified, broadcast-ready view with key highlights.  

**Issues Faced:**  
- None today. Setup went smoothly.


## September 28, 2025

**Planned Work:**  
- Research and shortlist data sources (ECI website, Kaggle, mock datasets).  
- Download at least 1 sample dataset (CSV).  

**Work Done:**  
- ✅ Researched possible election data sources:  
  1. **Election Commission of India (ECI)** – official data, constituency-wise results.  
  2. **Kaggle Datasets** – curated CSVs (2019 Indian General Election, state-level data). 

- ✅ Shortlisted Kaggle datasets as best for project prototyping because:  
  - Already available in **CSV/Excel** format.  
  - Includes **party-wise votes, constituencies, candidates**.  
  - Easy to clean and load into Power BI.  

- ✅ Downloaded **“Indian General Election 2019 Dataset” (CSV)** from Kaggle.  
  - Stored under `/data/raw/`.  
  - Columns include: `State`, `Constituency`, `Candidate`, `Party`, `Votes`, `Result`.  

**Issues Faced:**  
- ECI official data is authentic but comes in **PDF/HTML** format, which needs heavy manual cleaning.  
- Some datasets are very large → need preprocessing before Power BI import.  





