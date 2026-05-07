The repository contains Python scripts, R scripts, CSV files, and speech txt files.

The speeches folder contains the speeches from each candidate that were used in the following models.

Each Python script is its own model for the respective hypothesis. The files cannot be fully run without an API key:
- dominance_frame.ipynb
- pity_party.ipynb
- score_tests.ipynb

training_set.xlsx is an additional training set for the model used in pity_party.ipynb

The CSV files are the results from each of the models with the relevant characterstics being standardized (divided by the length of the speech then multiplied by 1000):
- dominance_frame_results.csv
- pity_party_scores.csv
- score_speeches.csv

statistical-analysis.qmd is an R-script that performs the statistical analyses (logitistic regression and Mann-Whitney U Tests)



