# Challenging Error Correction in Recognised Byzantine Greek

This is the repository of [HTREC shared task](https://www.aicrowd.com/challenges/htrec-2022). The 1st version of this repository was kindly developed by [@Connalia](https://github.com/Connalia/). The HTR model, the train and the original test data were developed by [@vivianpl](https://github.com/vivianpl). The synthetic test data along with unlimited help with the organisation are attributed to [@vasilikikou](https://github.com/vasilikikou).

## Dataset

The data folder comprises the dataset in the form of `train.csv` and `test.csv`, the latter including data from the `original_test.csv` and the `synthetic_test.csv`

## Code

* An exploratory data analysis appears in `eda.ipynb`
* The rule-based approach exists in `rbs.ipynb`, also described with pseudocode in `rbs_pseudocode.pdf`
* The ByT5 approach exists in `neural.ipynb`
