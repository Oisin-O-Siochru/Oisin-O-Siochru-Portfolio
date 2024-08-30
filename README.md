# Portfolio

Welcome to my GitHub portfolio! Here, you will find a collection of my work in big data analytics, machine learning, web scraping, and data visualization. Below are some highlights of my projects.

---

## M.E. Thesis: Big Data Analytics at JD.com

**Project Overview:**

Completed a Master's thesis focused on applying big data analytics to demand forecasting methods for e-commerce and online retailing using real-world data of over 2.5 million customers. This project involved:

- Implementing data preprocessing, manipulation, and structuring.
- Developing and training statistical ARIMA, machine learning neural network, and hybrid ARIMA-Artificial Neural Network models using refined datasets.
- Segmenting datasets for demographic analysis before forecasting retail demand.
- Presenting findings and business implications based on model evaluations.

**Results of Model Demand Forecasts:**

Below are some examples of model demand forecasts for the top 5 and 10th to 20th top product SKUs:

<p align="center">
  <img src="{{ "/images/SARIMA%20Forecast%20SKU%20Results.png" | prepend: site.baseurl | prepend: site.url }}" alt="SARIMA Forecast SKU Results" width="45%" />
  <img src="{{ "/images/LSTM%20Forecast%20SKU%20Results.png" | prepend: site.baseurl | prepend: site.url }}" alt="LSTM Forecast SKU Results" width="45%" />
</p>
<p align="center">
  <img src="{{ "/images/Rolling%20ARIMA%20Forecast%20SKU%20Results.png" | prepend: site.baseurl | prepend: site.url }}" alt="Rolling ARIMA Forecast SKU Results" width="45%" />
  <img src="{{ "/images/Hybrid%20ARIMA-ANN%20Forecast%20SKU%20Results.png" | prepend: site.baseurl | prepend: site.url }}" alt="Hybrid ARIMA-ANN Forecast SKU Results" width="45%" />
</p>

---

## Personal Project 1: YELP API Dublin Pub Data Visualization Project

**Project Overview:**

Utilized the YELP Fusion API to collect raw pub data from the greater Dublin area and applied preprocessing steps (cleaning, filtering) to parse raw data into CSV format. The project involved:

- Presenting summary statistics on pub review counts, ratings, and pricing ranges across Dublin both graphically and with mapping visualization.
  
**Results of Statistical Summary:**

<p align="center">
  <img src="{{ "/images/Generalvis.png" | prepend: site.baseurl | prepend: site.url }}" alt="General Visualization" width="45%" />
  <img src="{{ "/images/Boxplots.png" | prepend: site.baseurl | prepend: site.url }}" alt="Boxplots" width="45%" />
</p>

**Mapping Visualizations:**

- **Zip codes by number of reviews**

<p align="center">
  <img src="{{ "/images/Review%20count.png" | prepend: site.baseurl | prepend: site.url }}" alt="Review count by Zip Code" width="60%" />
</p>

- **Zip codes by average rating**

<p align="center">
  <img src="{{ "/images/Rating.png" | prepend: site.baseurl | prepend: site.url }}" alt="Rating by Zip Code" width="60%" />
</p>

---

## Academic Project 1: Football API Data Visualization Project

**Project Overview:**

Collected raw data from a public football league API using Python, stored in JSON for analysis. The project involved:

- Applying preprocessing steps (cleaning, filtering & integration).
- Characterizing and visualizing data using tables and graphics with Python packages such as NumPy, Pandas, Matplotlib, and Seaborn.
- Summarizing insights gained from the analysis of datasets.

---

## Academic Project 2: Web Scraping Text Classification Project

**Project Overview:**

Scraped a corpus of news stories through parsing web page HTML to extract specific text information. The project involved:

- Applying preprocessing steps to create a numeric representation of documents suitable for training.
- Performing binary classification and multi-class classification using KNN with 5-fold cross-validation to classify news story categories.
- Utilizing Python packages such as scikit-learn, itertools, and Beautiful Soup.

**Results of Binary and Multi-class Classification:**

<p align="center">
  <img src="{{ "/images/Average%20accuracies%20of%20pair%20classification.png" | prepend: site.baseurl | prepend: site.url }}" alt="Average Accuracies of Pair Classification" width="45%" />
  <img src="{{ "/images/Average%20fold%20accuracies%20vs%20KNN%20of%20pair%20classification.png" | prepend: site.baseurl | prepend: site.url }}" alt="Average Fold Accuracies vs KNN of Pair Classification" width="45%" />
</p>

<p align="center">
  <img src="{{ "/images/Confusion%20Matrix%20for%20Film%20and%20Business.png" | prepend: site.baseurl | prepend: site.url }}" alt="Confusion Matrix for Film and Business" width="45%" />
  <img src="{{ "/images/Confusion%20Matrix%20for%20Film%20and%20Sport.png" | prepend: site.baseurl | prepend: site.url }}" alt="Confusion Matrix for Film and Sport" width="45%" />
</p>
<p align="center">
  <img src="{{ "/images/Confusion%20Matrix%20for%20Sport%20and%20Business.png" | prepend: site.baseurl | prepend: site.url }}" alt="Confusion Matrix for Sport and Business" width="45%" />
  <img src="{{ "/images/Confusion%20Matrix%20for%20all.png" | prepend: site.baseurl | prepend: site.url }}" alt="Confusion Matrix for All Categories" width="45%" />
</p>

---

*For more information on each project or to view the source code, please visit the respective repositories.*


