# Chinese names classifier

A pre-trained GRU model classifies the Romanized Chinese names into [1] names from Hong Kong ; [2] names from Mainland China; and [3] Company's names.

## Data
The raw data is not available in Github because of privacy concerns. Users can checkout `01_proc_data.ipynb` and `02_Model training.ipynb` for example data.

## Model
`02_Model training.ipynb` train the GRU model with processed data. The pre-trained model is availability in the `model` folder. 

## Example
Please check out `03_Example.ipynb` for usage of the pre-trained model. 

## Reference
[Cheung KS, Chan JT, Li S, Yiu CY. Anchoring and Asymmetric Information in the Real Estate Market: A Machine Learning Approach. Journal of Risk and Financial Management. 2021; 14(9):423. https://doi.org/10.3390/jrfm14090423](https://www.mdpi.com/1911-8074/14/9/423/pdf)