# Gibbs_States_Data
Data supporting findings as reported in arXiv:2012.03895

# Simple snippets to import files with python code:

## For csv files:
import pandas as pd
dataframe = pd.read_csv(csv_path)
print('Data table is')
print(dataframe)

## For npz files:
import numpy as np
datanpz = np.load(npz_path)
for f in datanpz.files:
    print('Element {} is \n',format(f),datanpz[f])
