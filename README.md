# Gibbs_States_Data
Data supporting findings as reported in arXiv:2012.03895

# Simple snippets to import files with python code:
Following you may copy some code snippets that will get you started using the data.

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

# Status

N / A = Not applies, there is no plotted array of data in the figure

X = Done

x = partially done

[ N/A ] Fig 1

[ N/A ] Fig 2

[] Fig 3

[] Fig 4

[ X ] Fig 5

[] Fig S1

[] Fig S2

[ N/A ] Fig S3

[ N/A ] Fig S4

[ N/A ] Fig S5

[ N/A ] Fig S6

[ N/A ] Fig S7

[ N/A ] Fig S8

[ N/A ] Fig S9

[ N/A ] Fig S10

[ N/A ] Fig S11

[ x ] Fig S12

[ X ] Fig S13

[] Fig S14

[] Fig S15

[] Fig S16

[] Fig S17
