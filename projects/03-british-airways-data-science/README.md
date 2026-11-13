# British Airways Data Science Job Simulation

**Forage job simulation; not employment at British Airways**

## Business question

Which variables help predict booking completion?

## Tools

Python, pandas, scikit-learn, Matplotlib and Excel

## Data and scope

Training data supplied through the British Airways Forage simulation. Source data is not included in this package.

## Findings and work completed

The saved notebook outputs report 50,000 records, 719 exact duplicate rows removed and 49,281 retained records. A preprocessing pipeline uses one-hot encoding and a class-weighted Random Forest. Stratified grouped splits keep identical input profiles together. Saved held-out scores: ROC-AUC 0.774, average precision 0.340 against a no-skill baseline of 0.149, precision 0.296 and recall 0.737. Booking origin has the largest permutation importance in this model.

## Recommendations and interpretation

The work demonstrates data preparation, grouped validation, model evaluation and interpretation. Predictive importance does not prove causation. The low precision also matters when evaluating any proposed operational use.

## Files

- [booking-variable-importance.png](booking-variable-importance.png)
- [booking-prediction-summary.pptx](booking-prediction-summary.pptx)

## Limitations and reproducibility

Metrics come from the uploaded notebook outputs; training was not rerun during portfolio preparation. The companion Excel lounge-demand model uses illustrative assumptions, not official airline policy. Original lounge workbooks contain supplied schedule data and remain outside this public-upload starter pending a redistribution check.

Prepared by Shramana Das.

## Run the notebook

Install the packages in `requirements.txt`, obtain the authorised `customer_booking.csv` from the simulation and place it beside `booking-prediction.ipynb`. Open the notebook in Jupyter and run cells in order. Package versions were not captured in the original upload, so exact reproduction is not guaranteed.

[View completed notebook](booking-prediction.ipynb). The original starter notebook is not included.
