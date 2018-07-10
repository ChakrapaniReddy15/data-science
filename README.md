# data-science
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd

pd.read_json
# Importing the dataset
from tabula import read_pdf

df = read_pdf('chakri.pdf')
X = df.iloc[1:2,:-1].values
y = df.iloc[:,4].values

read_pdf('chakri.pdf',output_format='json')
read_pdf('chakri.pdf',output_format='tsv')
