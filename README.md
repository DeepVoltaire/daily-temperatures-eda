daily-temperatures-eda
# Project No. 3: Daily Temperatures EDA (Global, Europe, Austria)

This exploratory analysis looks at global temperatures between 1995 and 2019 and explores Europe and Austria in more detail.

After cleaning the dataset, the data is explored on three levels: on a global, European, and Austrian one. To visualize the data in order to answer the questions above, the libraries seaborn and matplotlib are used, including lineplots, barplots, boxplots, violinplots, histograms, and heatmaps.

### Global

<b>1. How did yearly/monthly global temperatures change between 1995 and 2019?</b>

![1a](https://github.com/HeleneFabia/daily-temperatures-eda/blob/master/images/1a.png)
![1b](https://github.com/HeleneFabia/daily-temperatures-eda/blob/master/images/1b.png)

<b>2. How do average temperatures of different regions in the world differ from each other and how did they change over time?</b>

![2a](https://github.com/HeleneFabia/daily-temperatures-eda/blob/master/images/2a.png)
![2c](https://github.com/HeleneFabia/daily-temperatures-eda/blob/master/images/2c.png)

<b>3. What are the hottest and coldest countries in the world?</b>

![3a](https://github.com/HeleneFabia/daily-temperatures-eda/blob/master/images/3a.png)
![3b](https://github.com/HeleneFabia/daily-temperatures-eda/blob/master/images/3b.png)

### Europe

<b>4. How are average European temperatures distributed?</b>


<b>5. How do average temperatures of different European countries compare to each other?</b>


<b>6. How did monthly temperatures change in Europe between 1995 and 2019?</b>




### Austria

<b>7. How are average Austrian temperatures distributed?</b>


<b>8. How did ealry/monthly temperatures change in Austria between 1995 and 2019?</b>


<b>9. What are the average temperatures in Austria each month?</b>



### Problems I faced and how I solved them1a1b
- Some countries, above all in Africa, had a lot of missing temperature values (as  high as 80%). Thus, I decided to fill any missing temperatures with the mean temperature of the respective month and city. However, this was not possible for every city, since some of them lacked entire months of temperature data. So for those countries, I filled the missing values with the overall mean of the respective city. Another idea would have been to fill the missing temperature with the temperature of the previous day (however, for those cities with entire months missing, this again could have proven problematic).
- conversion between Celsius and Fahrenheit, -99, 

Data from: https://www.kaggle.com/sudalairajkumar/daily-temperature-of-major-cities
