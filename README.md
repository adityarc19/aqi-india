# Air Quality Index (AQI) across and cities in India

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
* It contains air quality data and AQI (Air Quality Index) at hourly and daily level of various stations across multiple cities in India.
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


