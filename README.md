# Challenging Error Correction in Recognised Byzantine Greek

This is the repository of [HTREC shared task](https://www.aicrowd.com/challenges/htrec-2022). The 1st version of this repository was kindly developed by [@Connalia](https://github.com/Connalia/). The HTR model, the train and the original test data were developed by [@vivianpl](https://github.com/vivianpl). The synthetic test data along with unlimited help with the organisation are attributed to [@vasilikikou](https://github.com/vasilikikou).

## Dataset

The data folder comprises the dataset in the form of `train.csv` and `test.csv`, the latter including data from the `original_test.csv` and the `synthetic_test.csv`

## Code

* An exploratory data analysis appears in `eda.ipynb`
* The rule-based approach exists in `rbs.ipynb`, also described with pseudocode in `rbs_pseudocode.pdf`
* The ByT5 approach exists in `neural.ipynb`

## Cite
For work on error detection, please cite the following study:
```
@inproceedings{pavlopoulos-etal-2023-detecting,
    title = "Detecting Erroneously Recognized Handwritten Byzantine Text",
    author = "Pavlopoulos, John  and Kougia, Vasiliki and Platanou, Paraskevi  and Essler, Holger",
    editor = "Bouamor, Houda  and Pino, Juan  and Bali, Kalika",
    booktitle = "Findings of the Association for Computational Linguistics: EMNLP 2023",
    month = dec,
    year = "2023",
    address = "Singapore",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2023.findings-emnlp.524",
    doi = "10.18653/v1/2023.findings-emnlp.524",
    pages = "7818--7828",
}
```

For citing the HTREC challenge on error correction, please cite the following study ([here](https://doi.org/10.21203/rs.3.rs-2921088/v3) for a preprint):
```
@article{pavlopoulos-etal-2024-challenge,
  title={Challenging Error Correction in Recognised Byzantine Greek},
  author={Pavlopoulos, John and Kougia, Vasiliki and Arias, Esteban Garces and Platanou, Paraskevi and Shabalin, Stepan and Liagkou, Konstantina and Papadatos, Emmanouil and Essler, Holger and Camps, Jean-Baptiste and Franz Fischer},
  year={2024},
  publisher= "Association for Computational Linguistics",
  booktitle= "Proceedings of the first workshop on machine learning for ancient languages",
  address = "Bangkok, Thailand",
  month = "August"
}
```
