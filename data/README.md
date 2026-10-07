# Data

This project uses the **Bank Marketing (with social/economic context)** dataset from the UCI Machine Learning Repository.

I do not include the raw CSV in this repository. Download the full file named `bank-additional-full.csv` from the UCI Bank Marketing dataset and place it in this folder before running the notebook.

Expected path:

```text
data/bank-additional-full.csv
```

The full dataset contains **41,188 rows and 21 columns** before cleaning. In the notebook, I remove 12 exact duplicate rows, leaving **41,176 observations** for analysis.

## Citation

S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, 62 (2014), 22–31. https://doi.org/10.1016/j.dss.2014.03.001

The dataset documentation notes that `duration` should not be used for a realistic pre-call prediction model because call duration is only known after the call has taken place. The notebook keeps it for exploratory analysis and excludes it from modelling.
