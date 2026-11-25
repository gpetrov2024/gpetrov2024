# Grace Petrov

**From unstructured data to decisive action.** I build 0-to-1 data products and full-stack decision models that turn entrenched business problems into measured strategy and impact.

I'm a BBA candidate at Emory's Goizueta Business School (Information Systems & AI) and an AI Research Fellow at Emory's Center for AI Learning. My background is client-facing work on tight timelines with nonprofit and Fortune 500 organizations, where I've applied data analysis, machine learning, market research, and financial modeling to strategy, operations, customer insights, and technology implementation. More recently I've moved from analysis into building: software and data products that make complex information accessible and actionable.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-gracepetrov-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/gracepetrov/)
[![Email](https://img.shields.io/badge/Email-gpetrov2024@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:gpetrov2024@gmail.com)

---

## Selected work

### Grant Copilot
*Emory capstone, 2026. Top contributor.*

**The problem:** Grant applications are won on evidence of need, but the best source of local evidence, U.S. Census data, is spread across thousands of variables, geographies, and yearly releases. Small nonprofits rarely have an analyst to dig through it, so they either skip the data or cite numbers they can't trace back to a source, and both weaken an application.

**What it does:** A grant writer asks a plain-English question (*"I'm writing a food pantry grant for Southwest Atlanta"*) and gets back a cited paragraph of statistics, trends, and peer comparisons. Every number traces to a specific Census variable, year, and geography, so the writer can defend it to a funder.

**My contributions:**
- Built peer matching that stays valid across Census releases, plus support for questions spanning several years
- Added follow-up questions that keep the context of the session, and redesigned the answer and loading screens for non-technical users
- Hardened the evidence and export pipeline so numbers in an exported narrative can't drift from their sources

`Python` `Gemini / Vertex AI` `FAISS` `SpatiaLite` `Census ACS` `Docker`
*Private repo. Demo available on request.*

### [AI-Powered SAS to Python Migration](https://github.com/gpetrov2024/Abt-Global-1B-ai-powered-sas-migration/tree/star-ratings-ui/app)
*With Abt Global, Fall 2026*

**The problem:** Public agencies such as the Centers for Medicare & Medicaid Services still run critical analytics on SAS, which carries high licensing costs and a shrinking talent pool. Moving to Python by hand is slow and error-prone: every program has to be translated, tested, and documented, and the business logic buried in old code is easy to lose along the way.

**What it does:** An LLM-assisted workflow that translates SAS programs into Python, checks that the outputs match, flags differences, and documents the underlying logic. It is tested on the real pipeline behind CMS's Overall Hospital Quality Star Ratings, a public rating patients use to compare hospitals.

**My contributions:**
- **Translated and validated Program 1**, the first-stage group scoring for all five measure groups. Every column of every table was compared cell by cell against the original SAS datasets for 4,566 hospitals, and results match to within 1e-12. The translation deliberately keeps SAS's own arithmetic and missing-value handling so the outputs match exactly rather than approximately.
- **Built the end-to-end pipeline runner** that chains Programs 0 to 2 in memory, calling each program's validated functions so nothing is reimplemented.
- **Designed and built Star Ratings Studio, the team's web app**, so analysts can use the migrated pipeline without touching code:
  - *Run and compare:* run the pipeline on reference data or a new uploaded measure file, save runs, and compare two runs side by side to see every hospital whose rating moved
  - *Explore:* a ratings dashboard with a state map, rating distribution, and peer groups, plus a searchable hospital list and a detail page showing how each group score feeds the final star rating
  - *Trust:* a SAS parity page that checks all nine output tables against SAS, a methodology page mapping each stage to the SAS program it replaces, and a printable run report
  - *Reproducibility:* every run downloads with a manifest recording the input file's fingerprint, pipeline version, package versions, step timings, and validation results
  - Shipped as a single Docker image with CI that runs the tests on every pull request

`Python` `pandas` `FastAPI` `React` `TypeScript` `Tailwind` `pytest` `datacompy` `Docker` `GitHub Actions`

### [Baggage Volume Prediction for American Airlines](https://github.com/gpetrov2024/AmericanAirlines_BaggageOperations)

**The problem:** Airlines staff ground crews and baggage handling around how many bags they expect per flight. Underestimate and bags get delayed or mishandled, which hurts on-time performance and customers; overestimate and labor goes unused.

**What it does:** A neural network that forecasts checked-bag counts per flight from flight and schedule features, giving operations teams a sharper input for staffing decisions.

**My contributions:**
- Built a feed-forward network with learned embeddings for categorical flight features such as aircraft type and route
- Tuned 288 hyperparameter configurations with early stopping, then evaluated the best model on 24,711 held-out flights

`PyTorch` `pandas` `Parquet` `SQL`

---

## Toolkit

| | |
|---|---|
| **Languages & data** | Python, SQL, pandas, NumPy, DuckDB, SQLite, Parquet |
| **ML & NLP** | PyTorch, scikit-learn, spaCy, NLTK |
| **LLMs & retrieval** | OpenAI & Gemini APIs, RAG, embeddings, FAISS |
| **Cloud & tooling** | Google Cloud / Vertex AI, Docker, Git, Jupyter, REST APIs |
| **Analysis & communication** | Tableau, Plotly, Matplotlib, Excel financial modeling, market research |
