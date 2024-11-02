# cancer_final_year_project
import pandas as pd
import matplotlib.pyplot as plt
import seaborn as sns
from google.colab import drive
# Mount Google Drive
drive.mount('/content/drive')
# Load dataset
file_path = '/content/drive/My Drive/Thyroid_Cancer.csv'
df = pd.read_csv(file_path)
df.head(10)
