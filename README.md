# Fake News Detection System

## Internship Project — B.Tech Data Science

### Dataset
This project uses the WELFake dataset. Its Zenodo documentation reports **72,134 accessible news articles**, including **35,028 real** and **37,106 fake** articles. Label `0` = fake and `1` = real.

Dataset source: https://zenodo.org/records/4561253

The dataset is about 245 MB and is **not included in this ZIP**. The notebook downloads it automatically the first time it is run.

### Technologies
Python, Jupyter Notebook, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Joblib.

### Models
Logistic Regression, Multinomial Naive Bayes and Linear SVM. The notebook selects the model with the highest measured F1-score on the held-out test set.

### Run
1. Extract the ZIP.
2. Open the folder in Jupyter.
3. Open `Fake_News_Detection_Internship.ipynb`.
4. Run all cells from top to bottom.
5. The first run downloads the dataset (~245 MB).
6. Check `results/` for actual metrics and charts.
7. Test your own news at the final cell.

### GitHub
Suggested repository name: `Fake-News-Detection-System`

Do not upload the 245 MB dataset unless your repository/storage policy allows it. Keep the download instructions in this README.

### Academic citation
P. K. Verma, P. Agrawal, I. Amorim and R. Prodan, “WELFake: Word Embedding Over Linguistic Features for Fake News Detection,” IEEE Transactions on Computational Social Systems, 2021. DOI: 10.1109/TCSS.2021.3068519.

### Important limitation
This is an ML classifier, not an independent fact-checker. Its prediction depends on the training data and should not be treated as proof of truth or falsehood.
