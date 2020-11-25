# Air Quality Index (AQI) across stations and cities in India from 2015 to 2020

![aqi-logo][logo]

[logo]: https://github.com/adityarc19/aqi-india/blob/main/images/aqi-logo.jpeg?raw=true

------

I have taken an AQI dataset from Kaggle and performed some EDA on it as well as implemented a ***decision tree classiifer*** to classify the air quality into one of the six buckets:
 1. Good
 2. Moderate
 3. Satisfactory
 4. Poor
 5. Very Poor
 6. Severe

* The dataset is taken from [Kaggle](https://www.kaggle.com/rohanrao/air-quality-data-in-india).
* It contains air quality data and AQI (Air Quality Index) at hourly and daily level of various stations across multiple cities in India from 2015 to 2020.
* For this particular project, I have used just a part of the datasets provided in Kaggle, which contains day-wise city air pollution data.

Libraries used:
```
1. Numpy
2. Pandas
3. Seaborn
4. Chart Studio
5. Plotly
6. Pandas Profiling
7. PyCaret
```

I have used Pandas Profiling for performing exploratory data analysis and PyCaret for performing the machine learning classification task. Below are their installation commands:

For Pandas Profiling:
```
pip install pandas-profiling[notebook]

or

pip install https://github.com/pandas-profiling/pandas-profiling/archive/master.zip

or

conda install -c conda-forge pandas-profiling
```

For PyCaret:
```
#create a conda environment
conda create --name yourenvname python=3.6

#activate environment
conda activate yourenvname

#install pycaret
pip install pycaret

#create notebook kernel connected with the conda environment
python -m ipykernel install --user --name yourenvname --display-name "display-name"
```
---

### * Some EDA

**1. Dataframe**

![head][a]

[a]: https://github.com/adityarc19/aqi-india/blob/main/images/df-head.png

**2. AQI bucket chart**

![bucket][b]

[b]: https://github.com/adityarc19/aqi-india/blob/main/images/aqi-bucket-chart.png

**3. Pearson's correlations**

![corr][c]

[c]: https://github.com/adityarc19/aqi-india/blob/main/images/pearson's-correlations.png

**4. Most polluted cities**

![pol][d]

[d]: https://github.com/adityarc19/aqi-india/blob/main/images/max_pol_cities.png

**5. Least polluted cities**

![poll][e]

[e]: https://github.com/adityarc19/aqi-india/blob/main/images/min_pol_cities.png

**6. City wise pollutants analysis**

![city][i]

[i]: https://github.com/adityarc19/aqi-india/blob/main/images/city-wise.png?raw=true

**7. Yearly analysis**

![yearly][h]

[h]: https://github.com/adityarc19/aqi-india/blob/main/images/yearly-analysis.png?raw=true

---
I would like to thank [Parul Pandey](https://www.kaggle.com/parulpandey) as well as [Naresh Bhat](https://www.kaggle.com/nareshbhat) for providing some amazing data exploration techniques from which I've pulled here.
1. Parul Pandey's notebook: https://www.kaggle.com/parulpandey/breathe-india-covid-19-effect-on-pollution
2. Naresh Bhat's notebook: https://www.kaggle.com/nareshbhat/air-quality-analysis-eda-and-classification
------

### * Classification model used: Decision tree

I have used 'decision tree' as a classification model for this prediction problem based on the following results:

![mod][f]

[f]: https://github.com/adityarc19/aqi-india/blob/main/images/model-comparisons.png

Using decision tree for classification, confusion matrix for validation data:

![cm][g]

[g]: https://github.com/adityarc19/aqi-india/blob/main/images/confusion-matrix.png


---












