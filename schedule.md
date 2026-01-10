# Weekly Class Schedule

| Class | Date   | Topic                                                             | Tutorial   | Instructor | 
| ----: | ------ | ----------------------------------------------------------------- | ---------- | ---------- | 
|     1 | Jan 8  | Programming with data using Python |  No tutorial         | NT | 
|     2 | Jan 15 | Exploratory data analysis using Python | A1         | NT
|     3 | Jan 22 | Prediction and inference in statistical models - quantitative data | A2         | MF
|     4 | Jan 29 | Prediction and inference in statistical models - non-quantitative data | A3         | MF
|     5 | Feb 5  | Supervised learning models                                        | MT Review  | NT
|     -  | Feb 12 | **Midterm** (covers Weeks 1-5)                                    | *No tutorial* |
|     - | Feb 19 | **Reading Week**                                                  | -          | NT
|     6 | Feb 26 | Supervised learning models                                        | A4         | MF
|     7 | Mar 5  | Unsupervised learning models                                      | A5         | MF
|     8 | Mar 12 | Unsupervised learning models                                      | A6         | NT
|    9 | Mar 19 | Communicating information from models                             | A7         | NT
|    10 | Mar 26 | Ethical issues in modeling data                                   | A8         | MF
|    11 | Apr 2  | TBD                                                               | A9        | NT



## Description of Modules

### Programming with data using Python

#### Takeaways

- Recognize that not all data is numerical and is stored in different digital formats
- Use Python to analyse and manipulate data 
- Use pandas and related libraries to program and analyze data 
- Explain data science workflows 
- Use a Jupyter notebook to analyse data that originate in various formats and write text using markdown 


#### Key Exercises/ Things you should be able to do

- Use Python standard library to load and manipulate data 
- Use pandas and matplotlib to load, manipulate and analyse data 
- Explain data science workflows
 

### Exploratory data analysis using Python

#### Takeaways
 - Communicate EDA findings: pair concise visuals with one-sentence takeaways; save notebook-friendly figures; keep a reproducible workflow
 - Load and inspect datasets with pandas (CSV/JSON); check shape, dtypes, head/tail, info(), describe()
 - Tidy and clean data by handling missingness, fixing types/categories, removing duplicates/outliers, and parsing text/dates
 - Select appropriate summary statistics for numeric vs categorical data; compare groups with groupby/agg
 - Create quick univariate and bivariate visuals (hist/box/violin/bar; scatter/heatmaps/countplots) to surface patterns and issues
 - Diagnose distribution shape and scale effects; apply log or standardization when justified and interpret changes
 - Probe relationships while avoiding pitfalls (correlation caveats, Simpson's paradox); stratify and facet by key categories
 - Prevent common mistakes: avoid leakage and over-filtering, choose honest axes, and separate signal from noise while tracking assumptions
 - Communicate EDA findings with concise visuals and one-sentence takeaways; save reproducible, notebook-friendly outputs


#### Key Exercises/ Things you should be able to do

Here are solid **Key Exercises / things you should be able to do** for the EDA module (written in the same style as your first module). You can pick 5–8 of these.

#### Key Exercises / Things you should be able to do (EDA)

* Load a dataset and do a first-pass audit: `shape`, `dtypes`, `head/tail`, `info()`, missingness counts, duplicates
* Create a simple “EDA checklist” cell that you can reuse across notebooks (import, load, inspect, clean, summarize, visualize)
* Produce **univariate** summaries and visuals for key variables (hist/box for numeric, bar/count for categorical) and write a **one-sentence takeaway** under each
* Compare groups with `groupby()` + `agg()` and report differences using appropriate summary stats (mean/median/IQR for numeric; proportions for categorical)
* Identify and handle missing data thoughtfully (quantify missingness, decide drop vs impute, justify choice)
* Detect outliers and data quality issues (impossible values, typos, inconsistent categories) and document your fixes
* Explore **bivariate** relationships (scatterplots, boxplots by group, crosstabs/stacked bars) and interpret patterns without overclaiming causality
* Compute and interpret correlations carefully (numeric–numeric correlation matrix/heatmap; note confounding and nonlinearity)
* Demonstrate a “scale fix”: apply a log transform or standardization where appropriate and explain how interpretation changes
* Use faceting/stratification (e.g., `seaborn.FacetGrid` or small multiples) to check whether patterns persist across subgroups (Simpson’s paradox check)
* Save figures to disk with consistent sizing/naming and keep your workflow reproducible (same results when rerun)
* Write a short EDA “mini-report” section: 3–5 key findings, 2–3 caveats/assumptions, and 1–2 next analysis questions

### Prediction and inference in statistical models - quantitative data

:soon: