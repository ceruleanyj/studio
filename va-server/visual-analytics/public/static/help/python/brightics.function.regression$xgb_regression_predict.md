## Format
### Python
```python
from brightics.function.regression import xgb_regression_predict
res = xgb_regression_predict(prediction_col = ,group_by = )
res['out_table']
```

## Description
Using the result of 'XGB Regression Train', this function predicts with the input table.

---

## Properties
### VA
#### Inputs
1. **table**: table
2. **model**: model

#### Parameters
1. **Prediction Column Name**: Column name for pPrediction
   - Value type : String
   - Default : prediction
2. **Group By**: Columns to group by

#### Outputs
1. **out_table**: table

### Python
#### Inputs
1. **table**: table
2. **model**: model

#### Parameters
1. **prediction_col**: Column name for pPrediction
   - Value type : String
   - Default : prediction
2. **group_by**: Columns to group by

#### Outputs
1. **out_table**: table

