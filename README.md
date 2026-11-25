<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:0A2540,100:0A66C2&height=150&section=header&text=Grace%20Petrov&fontColor=ffffff&fontSize=44&fontAlignY=42&desc=From%20unstructured%20data%20to%20decisive%20action&descAlignY=68&descSize=16" alt="Grace Petrov. From unstructured data to decisive action." />

<p align="center">
  <a href="https://www.linkedin.com/in/gracepetrov/">LinkedIn</a> &nbsp;&nbsp;|&nbsp;&nbsp;
  <a href="mailto:gpetrov2024@gmail.com">gpetrov2024@gmail.com</a> &nbsp;&nbsp;|&nbsp;&nbsp;
  Atlanta, GA
</p>

I build 0-to-1 data products and full-stack decision models that convert entrenched business problems into measured strategy and impact. I am a BBA candidate at Emory University's Goizueta Business School and an AI Research Fellow at Emory's Center for AI Learning, with client-facing experience across nonprofit and Fortune 500 engagements.

## Case Studies

### Grant Copilot
*Emory University Capstone, 2026. Top contributor. Private repository, demo available upon request.*

<table>
<tr>
<th width="33%">Business Problem</th>
<th width="33%">Solution</th>
<th width="34%">My Contributions</th>
</tr>
<tr>
<td valign="top">Small nonprofits need quantitative evidence of community need to win grants, but U.S. Census data spans thousands of variables and releases, and few nonprofits have analysts to navigate it.</td>
<td valign="top">A grant writer asks a question in plain English and receives a cited narrative of statistics, trends, and peer comparisons, each traceable to a specific Census variable, year, and geography.</td>
<td valign="top">Peer-matching logic across Census releases, multi-year queries, session-aware follow-up questions, redesigned response interface, and export integrity.</td>
</tr>
</table>

`Python` `Gemini / Vertex AI` `FAISS` `SpatiaLite` `Census ACS` `Docker`

### AI-Powered SAS to Python Migration
*In partnership with Abt Global, Fall 2026.* [View the Star Ratings Studio application](https://github.com/gpetrov2024/Abt-Global-1B-ai-powered-sas-migration/tree/star-ratings-ui/app)

<table>
<tr>
<th width="33%">Business Problem</th>
<th width="33%">Solution</th>
<th width="34%">My Contributions</th>
</tr>
<tr>
<td valign="top">Agencies such as CMS run critical analytics on SAS, which carries high licensing costs and a shrinking talent pool. Manual migration is slow, error-prone, and risks losing institutional knowledge.</td>
<td valign="top">An LLM-assisted workflow that translates SAS to Python, verifies output parity, and documents the business logic, evaluated on the CMS Hospital Star Ratings pipeline.</td>
<td valign="top">Translated and validated Program 1 across 4,566 hospitals within 1e-12 of SAS, built the end-to-end pipeline runner, and designed and developed the Star Ratings Studio web application.</td>
</tr>
</table>

```mermaid
flowchart LR
    A[Legacy SAS programs] --> B[LLM-assisted translation]
    B --> C[Python pipeline]
    C --> D[Parity checks against SAS]
    D --> E[Star Ratings Studio]
```

<details>
<summary><b>Star Ratings Studio</b> &nbsp;|&nbsp; Web application features</summary>

<br>

Star Ratings Studio gives analysts full access to the migrated pipeline through a graphical interface.

- **Run and compare.** Users can run the pipeline on reference data or a newly uploaded measure file, save results, and compare two runs side by side to identify every hospital whose rating changed.
- **Explore.** A ratings dashboard presents a state-level map, rating distributions, and peer groups, along with a searchable hospital directory and detail pages that show how each group score contributes to the final star rating.
- **Validate.** A SAS parity page checks all nine output tables against the original SAS results, a methodology page maps each stage to the SAS program it replaces, and a printable report summarizes each run.
- **Reproduce.** Every run can be exported with a manifest that records the input file fingerprint, pipeline version, package versions, processing times, and validation results.
- **Deploy.** The application is packaged as a single Docker image, with continuous integration that runs the full test suite on every pull request.

</details>

`Python` `pandas` `FastAPI` `React` `TypeScript` `pytest` `Docker` `GitHub Actions`

### Baggage Volume Forecasting for American Airlines
[View the repository](https://github.com/gpetrov2024/AmericanAirlines_BaggageOperations)

<table>
<tr>
<th width="33%">Business Problem</th>
<th width="33%">Solution</th>
<th width="34%">My Contributions</th>
</tr>
<tr>
<td valign="top">Ground-crew staffing depends on expected bags per flight. Underestimates delay baggage and hurt customer satisfaction. Overestimates create excess labor costs.</td>
<td valign="top">A neural network that forecasts checked-bag volume per flight from flight and schedule attributes to support staffing decisions.</td>
<td valign="top">Feed-forward architecture with categorical embeddings, 288-configuration hyperparameter search, and evaluation on 24,711 held-out flights.</td>
</tr>
</table>

`PyTorch` `pandas` `Parquet` `SQL`

## Technical Skills

<table>
  <tr><td><b>Languages and Data</b></td><td>Python, SQL, TypeScript, pandas, NumPy, DuckDB, SQLite, Parquet</td></tr>
  <tr><td><b>Machine Learning and NLP</b></td><td>PyTorch, scikit-learn, spaCy, NLTK</td></tr>
  <tr><td><b>Generative AI and Retrieval</b></td><td>OpenAI and Gemini APIs, RAG, embeddings, FAISS</td></tr>
  <tr><td><b>Applications and Cloud</b></td><td>FastAPI, React, Google Cloud, Vertex AI, Docker, GitHub Actions, REST APIs</td></tr>
  <tr><td><b>Analytics and Business</b></td><td>Tableau, Plotly, Matplotlib, Excel financial modeling, market research</td></tr>
</table>
