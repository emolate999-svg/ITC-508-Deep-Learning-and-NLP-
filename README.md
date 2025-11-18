Why We Conduct This Project

TThe aim of the project is to tackle the increased demand for automated and very high-quality headline generation in digital journalism. The current situation is such that news organizations are flooding the market with huge amounts of content every day, and the manual writing of headlines is a time-consuming process that requires a lot of editorial expertise. There are some AI headline generators already in place, but unfortunately, most of them apply either generic templates or heuristic approaches based on keywords which lead to the production of boring headlines that are neither accurate in terms of context nor are they in the exact style of the journalistic piece. 

The project is focused on fine-tuning the cutting-edge Transformer models—T5-Small and Facebook BART—using the professional pairing of news articles and their corresponding headlines. The final goal is to develop a system that can offer headlines that are brief, easy to read, aware of the context, and stylistically aligned with the standards practiced in a professional newsroom. As part of this project, experimentation will involve the manual tuning of the hyperparameters as well as the automated optimization through GridSearch/RandomSearch to find out scientifically the best-performing model configurations.

All in all, this study proves how much it is worth to morph a general-purpose language model into a specialized journalistic tool thus enhancing editorial efficiency with the aid of innovations in digital publishing. Moreover, the research work helps in the realization of technological advancement and is in line with one of the United Nations Sustainable Development Goals (goal 9: Industry, Innovation, and Infrastructure) as it facilitates the passage of AI-driven advancements in the media and communication systems.


---

NLP Model Fine-Tuning — Three Musketeers Project

This repository contains all experiment files, notebooks, and logs produced during Exercise F2 and Exercise F3, focusing on **fine-tuning NLP models**, **hyperparameter experimentation**, and **automated tuning using GridSearch / RandomSearch**.

---

Overview

The project applies fine-tuning on transformer-based models—**T5-Small** and **Facebook BART**—to improve performance on a text-based NLP task using systematic hyperparameter tuning and search optimization.
All model runs, experiment iterations, and performance outcomes are documented for transparency and reproducibility.

---

Repository Contents & Explanation

| File / Folder                                               | Description                                                                                 |
| ----------------------------------------------------------- | ------------------------------------------------------------------------------------------- |
| **EF3_ThreeMusketeers_T5_Small_ThreeMusketeers.ipynb**      | Google Colab notebook performing full fine-tuning on the **T5-Small** model (Exercise F3).  |
| **EF3_ThreeMusketeers_Facebook_Bart_ThreeMusketeers.ipynb** | Google Colab notebook performing full fine-tuning on **Facebook BART** (Exercise F3).       |
| **T5_Small_ThreeMusketeers.ipynb**                          | Baseline fine-tuning notebook for T5-Small before applying F3 search techniques.            |
| **Facebook_Bart_ThreeMusketeers.ipynb**                     | Baseline fine-tuning notebook for Facebook BART before applying F3 search techniques.       |
| **TM_Ground-Truth_Test_Set.csv**                            | Ground-truth dataset used for model evaluation and inference testing.                       |
| **ThreeMusketeers_Automated_Experiment_Logs.xlsx**          | Log sheet documenting automatic parameter search experimentation (GridSearch/RandomSearch). |
| **ThreeMusketeers_Manual_Experiment_Logs.xlsx**             | Log sheet recording manual hyperparameter tuning results.                                   |
| **Arive_ExperimentLogs.xlsx**                               | Manual F2 experiment results by **Arive**.                                                  |
| **EF3_LordCedricArive_ExperimentationLogs.xlsx**            | F3 experiment results by **Arive** using GridSearch/RandomSearch.                           |
| **EF3_LlamadoJuanMiguel_ExperimentationLogs.xlsx**          | F3 hyperparameter experiment logs by **Llamado**.                                           |
| **Llamado_ExperimentLogs.xlsx**                             | Manual F2 experiment results by **Llamado**.                                                |
| **ExperimentLogs_Molate.xlsx**                              | Manual F2 experiment results by **Molate**.                                                 |
| **GridSearch_RandomSearch_ExperimentLogs Molate.xlsx**      | Automated F3 experiment logs by **Molate** using GridSearch/RandomSearch.                   |
| **README.md**                                               | Documentation file describing the purpose and structure of the project.                     |


The project evaluates two transformer architectures:

| Model             | Baseline Phase          | Optimization Phase             |
| ----------------- | ----------------------- | ------------------------------ |
| **T5-Small**      | Manual fine-tuning (F2) | GridSearch / RandomSearch (F3) |
| **Facebook BART** | Manual fine-tuning (F2) | GridSearch / RandomSearch (F3) |

Each team member performed:

* Manual hyperparameter experimentation (Exercise F2)
* Automated parameter search using **GridSearch or RandomSearch** (Exercise F3)

All performance changes (Accuracy / F1-Score) from every configuration are tracked in the Excel log files.



Exercise F3

Exercise F3 improves model tuning efficiency by:

* Automatically exploring multiple hyperparameter combinations
* Identifying the **best-performing configuration** based on evaluation metrics
* Reducing time spent on trial-and-error manual tuning

This enables more systematic and data-driven optimization.



Contributors

| Member                          | Contributions                                      |
| ------------------------------- | -------------------------------------------------- |
| Arive                           | Manual F2 experiments & F3 tuning                  |
| Llamado                         | Manual F2 experiments & F3 tuning                  |
| Molate                          | Manual F2 experiments & F3 tuning                  |


