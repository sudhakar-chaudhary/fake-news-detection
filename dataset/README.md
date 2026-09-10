# Dataset

This project uses the **ISOT Fake News Detection Dataset** from Kaggle.

The dataset contains two files:

- `Fake.csv` — fake news articles
- `True.csv` — real news articles

## Source

Kaggle dataset:
https://www.kaggle.com/datasets/clemletbisaillon/fake-and-real-news-dataset

The original CSV files are not stored directly in this GitHub repository because of their large file size.

Download the dataset from Kaggle and place:

```text
Fake.csv
True.csv


Then click **Commit changes**.

### Your Python code

After downloading the dataset from Kaggle, your notebook can use:

```python
import pandas as pd

fake = pd.read_csv("dataset/Fake.csv")
true = pd.read_csv("dataset/True.csv")
