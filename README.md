<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/banner-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/banner-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg" />
  <img width="100%" src="assets/banner-light.svg" alt="Grace Petrov. From unstructured data to decisive action." />
</picture>

<p align="center">
  <a href="https://www.linkedin.com/in/gracepetrov/">LinkedIn</a>&emsp;&emsp;<a href="mailto:gpetrov2024@gmail.com">gpetrov2024@gmail.com</a>&emsp;&emsp;Atlanta,&nbsp;GA
</p>

I build 0-to-1 data products and full-stack decision models that convert entrenched business problems into measured strategy and impact. I am a BBA candidate at Emory University's Goizueta Business School and an AI Research Fellow at Emory's Center for AI Learning, with client-facing experience across nonprofit and Fortune 500 engagements.

## Selected Work

<div>
<a href="#grant-copilot"><picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/row-grant-copilot-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/row-grant-copilot-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/row-grant-copilot-dark.svg" />
  <img width="100%" src="assets/row-grant-copilot-light.svg" alt="Grant Copilot. Gives nonprofit grant writers cited U.S. Census evidence for every claim they make to a funder." />
</picture></a>
<a href="https://github.com/gpetrov2024/Abt-Global-1B-ai-powered-sas-migration/tree/star-ratings-ui/app"><picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/row-sas-migration-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/row-sas-migration-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/row-sas-migration-dark.svg" />
  <img width="100%" src="assets/row-sas-migration-light.svg" alt="SAS to Python Migration. Moves the CMS hospital star-rating pipeline off SAS, validated cell by cell for 4,566 hospitals." />
</picture></a>
<a href="https://github.com/gpetrov2024/AmericanAirlines_BaggageOperations"><picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/row-baggage-forecasting-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/row-baggage-forecasting-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/row-baggage-forecasting-dark.svg" />
  <img width="100%" src="assets/row-baggage-forecasting-light.svg" alt="Baggage Forecasting. Predicts checked bags per flight so ground crews can be staffed to real demand." />
</picture></a>
</div>

## Case Studies

<a name="grant-copilot"></a>
<div>
<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/sheet-grant-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/sheet-grant-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/sheet-grant-dark.svg" />
  <img width="100%" src="assets/sheet-grant-light.svg" alt="Grant Copilot. Census evidence for grant writers, cited down to the variable. Emory University, 2026, top contributor. Private repository, demo on request. Business problem: Small nonprofits need quantitative evidence of community need to win grants, but U.S. Census data spans thousands of variables and releases, and few nonprofits have analysts to navigate it. Solution: A grant writer asks a question in plain English and receives a cited narrative of statistics, trends, and peer comparisons, each traceable to a specific Census variable, year, and geography. My contributions: Peer-matching logic across Census releases, multi-year queries, session-aware follow-up questions, redesigned response interface, and export integrity. Built with Python, Gemini / Vertex AI, FAISS, SpatiaLite, Census ACS, Docker." />
</picture>
</div>

<a name="ai-powered-sas-to-python-migration"></a>
<div>
<a href="https://github.com/gpetrov2024/Abt-Global-1B-ai-powered-sas-migration/tree/star-ratings-ui/app"><picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/sheet-sas-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/sheet-sas-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/sheet-sas-dark.svg" />
  <img width="100%" src="assets/sheet-sas-light.svg" alt="AI-Powered SAS to Python Migration. Matched SAS output for 4,566 hospitals within 1 x 10 to the minus 12. Abt Global, fall 2026, client partnership. Star Ratings Studio on GitHub. Business problem: Agencies such as CMS run critical analytics on SAS, which carries high licensing costs and a shrinking talent pool. Manual migration is slow, error-prone, and risks losing institutional knowledge. Solution: An LLM-assisted workflow that translates SAS to Python, verifies output parity, and documents the business logic, evaluated on the CMS Hospital Star Ratings pipeline. My contributions: Translated and validated Program 1 across 4,566 hospitals within 1 x 10 to the minus 12 of SAS, built the end-to-end pipeline runner, and designed and developed the Star Ratings Studio web application. Built with Python, pandas, FastAPI, React, TypeScript, pytest, Docker, GitHub Actions." />
</picture></a>
</div>

[View the Star Ratings Studio application](https://github.com/gpetrov2024/Abt-Global-1B-ai-powered-sas-migration/tree/star-ratings-ui/app)

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/flow-sas-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/flow-sas-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/flow-sas-dark.svg" />
  <img width="100%" src="assets/flow-sas-light.svg" alt="Pipeline: legacy SAS programs, LLM-assisted translation, Python pipeline, parity checks against SAS, Star Ratings Studio." />
</picture>

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

<a name="baggage-volume-forecasting"></a>
<div>
<a href="https://github.com/gpetrov2024/AmericanAirlines_BaggageOperations"><picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/sheet-baggage-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/sheet-baggage-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/sheet-baggage-dark.svg" />
  <img width="100%" src="assets/sheet-baggage-light.svg" alt="Baggage Volume Forecasting. Checked bags per flight, forecast for ground-crew staffing. American Airlines, baggage operations. Public repository on GitHub. Business problem: Ground-crew staffing depends on expected bags per flight. Underestimates delay baggage and hurt customer satisfaction. Overestimates create excess labor costs. Solution: A neural network that forecasts checked-bag volume per flight from flight and schedule attributes to support staffing decisions. My contributions: Feed-forward architecture with categorical embeddings, 288-configuration hyperparameter search, and evaluation on 24,711 held-out flights. Built with PyTorch, pandas, Parquet, SQL." />
</picture></a>
</div>

[View the repository](https://github.com/gpetrov2024/AmericanAirlines_BaggageOperations)

## Technical Skills

<picture>
  <source media="(max-width: 600px) and (prefers-color-scheme: dark)" srcset="assets/plate-skills-mobile-dark.svg" />
  <source media="(max-width: 600px)" srcset="assets/plate-skills-mobile-light.svg" />
  <source media="(prefers-color-scheme: dark)" srcset="assets/plate-skills-dark.svg" />
  <img width="100%" src="assets/plate-skills-light.svg" alt="Technical skills legend. Languages and Data: Python, SQL, TypeScript, pandas, NumPy, DuckDB, SQLite, Parquet. Machine Learning and NLP: PyTorch, scikit-learn, spaCy, NLTK. Generative AI and Retrieval: OpenAI and Gemini APIs, RAG, embeddings, FAISS. Applications and Cloud: FastAPI, React, Google Cloud, Vertex AI, Docker, GitHub Actions, REST APIs. Analytics and Business: Tableau, Plotly, Matplotlib, Excel financial modeling, market research." />
</picture>
