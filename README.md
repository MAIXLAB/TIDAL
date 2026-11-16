# TIDAL Course Code

Teaching code for Project TIDAL, organized by module and delivery format. Code filenames begin with the corresponding module number.

**No datasets are included. Users are responsible for requesting and obtaining any required data access and permissions from the relevant data owners before using the code.** See [data sources for each code file](DATA_SOURCES.md).

| Module | Topic | Delivery format | Code name |
| --- | --- | --- | --- |
| 1.1 | Epidemiology and IPV measurement | Asynchronous online | — |
| 1.2 | Available data sources | Asynchronous online | — |
| 1.3.1 | Introduction to R and RStudio | Asynchronous online | [1.3.1-introduction-to-r.R](1.3.1-introduction-to-r.R)<br>[1.3.1-first-r-script.R](1.3.1-first-r-script.R) |
| 1.3.2 | Data wrangling | Asynchronous online | [1.3.2-data-wrangling.R](1.3.2-data-wrangling.R) |
| 1.3.3 | Data visualization | Asynchronous online | [1.3.3-data-visualization.R](1.3.3-data-visualization.R)<br>[1.3.3-prams-visualization.Rmd](1.3.3-prams-visualization.Rmd) |
| 1.3.4 | Missing data and sampling weights | On-campus intensive | [1.3.4-missing-data-and-weights.R](1.3.4-missing-data-and-weights.R) |
| 1.3.5 | Statistical tests and models | On-campus intensive | [1.3.5-statistical-tests-and-models.R](1.3.5-statistical-tests-and-models.R)<br>[1.3.5-prams-statistical-tests.Rmd](1.3.5-prams-statistical-tests.Rmd)<br>[1.3.5-prams-regression-and-auc.Rmd](1.3.5-prams-regression-and-auc.Rmd) |
| 1.3.6 | Reproducible research | On-campus intensive | [1.3.6-prams-report-full-data.Rmd](1.3.6-prams-report-full-data.Rmd)<br>[1.3.6-prams-report-teaching-subset.Rmd](1.3.6-prams-report-teaching-subset.Rmd) |
| 1.4.1 | Introduction to machine learning | Asynchronous online | — |
| 1.4.2 | ML applications in health research | Asynchronous online | — |
| 1.4.3 | Machine learning in action | Asynchronous online | [1.4.3-machine-learning-in-action.qmd](1.4.3-machine-learning-in-action.qmd)<br>[1.4.3-code-along.qmd](1.4.3-code-along.qmd) |
| 1.4.4 | Fundamentals and algorithm intuitions | On-campus intensive | — |
| 1.4.5 | ML evaluation, fairness, and explainability | On-campus intensive | — |
| 1.4.6 | Guided hands-on machine learning | On-campus intensive | [1.4.6-purple-instruction.Rmd](1.4.6-purple-instruction.Rmd)<br>[1.4.6-purple-practice.Rmd](1.4.6-purple-practice.Rmd) |
| 1.5.1 | Theoretical NLP background | Asynchronous online | — |
| 1.5.2 | Fundamental NLP problems | Asynchronous online | — |
| 1.5.3 | Data/text mining pipelines | Asynchronous online | — |
| 1.5.4 | Introduction to NLP | On-campus intensive | [1.5.4-introduction-to-nlp.Rmd](1.5.4-introduction-to-nlp.Rmd) |
| 1.5.5 | Text representation and similarities | On-campus intensive | [1.5.5-text-representation-and-similarities.Rmd](1.5.5-text-representation-and-similarities.Rmd) |
| 1.5.6 | Prompting large language models | On-campus intensive | — |
| 1.5.7 | Supervised ML in NLP | On-campus intensive | [1.5.7-supervised-ml-in-nlp.Rmd](1.5.7-supervised-ml-in-nlp.Rmd) |
| 1.5.8 | NLP evaluation and validation | On-campus intensive | [1.5.8-evaluation-and-validation.Rmd](1.5.8-evaluation-and-validation.Rmd) |
| 2.1 | Trauma-informed computing | Synchronous online | — |
| 2.2 | Trauma-informed mHealth tools | Asynchronous + synchronous online | — |
| 2.3 | Trauma-informed digital games | Asynchronous + synchronous online | — |
| 3.1 | Ethics, bias, and digital health | Synchronous online | — |
| 3.2 | Digital security and tech abuse | Synchronous online | — |

“—” means no separate code file was identified for that lesson. Some examples and activities are contained in the lecture materials. Delivery formats for Modules 2.2 and 2.3 follow the 2026 course materials.

## Additional module resources

These files support the parent module; their exact lesson assignment is not confirmed.

| Module | Topic | Delivery format | Code name |
| --- | --- | --- | --- |
| 1.3 | Additional PRAMS descriptive analysis and SAS import helper | Supporting material | [1.3-prams-descriptive-analysis.Rmd](1.3-prams-descriptive-analysis.Rmd)<br>[1.3-prams-sas-import.sas](1.3-prams-sas-import.sas) |
| 1.4 | Additional PRAMS machine learning case studies | On-campus intensive — related practice | [1.4-prams-case-study.Rmd](1.4-prams-case-study.Rmd)<br>[1.4-prams-self-exploration.Rmd](1.4-prams-self-exploration.Rmd) |

## Using the code

Review [data sources and input filenames](DATA_SOURCES.md) before running a file. Keep authorized data local and use the filenames expected by the original code. Open the included `1.4.3-machine-learning.Rproj` for the Quarto lesson so its relative paths resolve from this folder. The `images/` folder contains instructional illustrations used by that lesson, not datasets.

Code contents are unchanged; filenames have been standardized. See [original filenames and attribution](SOURCES.md). The two original 1.4.3 Quarto files contain an extra opening YAML delimiter that may need correction before rendering. Code has not been execution-tested. The full-data and teaching-subset PRAMS report templates require different inputs.
