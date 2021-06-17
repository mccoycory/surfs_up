# surfs up

## Overview 

The overview of this project was to help our friends in the Hawaii run some data anaylsis on weather trends so they can make an data driven decision on whether or not they should open a surf shop. The data was given to us in a SQLlite database form. We used our knowledge of SQLlite and sqlalchemy to import and query this data into python. The file step in this project was to use the FLASK app to present the data to the investors. We need to determine weather temperature trends around the seasons. So we took the Month of June and the Month of December to run our analysis. 

## Results 

The ability to import this data and use the pandas lib. in python allowed us to run quick analysis. Please reference below for screenshots of the temperature for June and December. 

### June Statistic Temp. Table
![June Table](https://github.com/mccoycory/surfs_up/blob/main/Resources/June%20Temps%20Table.png)

### December Statistic Temp. Table

![Dec Table](https://github.com/mccoycory/surfs_up/blob/main/Resources/December%20Temps%20Tables.png)

#### Compare and Contrast 

- At first look, you can tell there is a difference in total records between June and December. Knowing the count is always important because you want to compare similar data points and counts. It would be hard to compare a data set with 2000 records vs a data set with 10 records. This data set has similar records ~1700 and ~1500 so we can be confident in our data anaylsis.

- When looking at the mean temperature between June and December, I was surprised there was only a difference between 5 degrees. This both important and good for our friends in Hawaii. With a slight difference in temperature between the summer and winter seasons, we can be confident that business can be open year around. 

- Along with average, I think it is important to compare median and max. Both data sets are statistically normal as there mean and median values are very close to each other. With the max temperatures being about the same during both months. This shows us we can be confident in our conclusion that the weather is perfect year around. 

## Summary 

Based on our analysis of temps between months, I would recommended that this is a safe investment. The weather should be allow for year around business and with year about business means dollars in our pockets. However, if there are additionally reservations about the investment. One could run the following queries to study the amount of rainfall is expected during these months. Additionally, I would pull some Weather storm data... it would be good to know if and when there is a storm season and what we as business owners can do to midigate risk. 

### June Rainfall query
![June query](https://github.com/mccoycory/surfs_up/blob/main/Resources/query%20for%20rain%20in%20june.png)

### December Rainfall query 
![Dec query](https://github.com/mccoycory/surfs_up/blob/main/Resources/query%20for%20rain%20in%20dec.png)

### June Rainfall Table 

![June Rainfall Table](https://github.com/mccoycory/surfs_up/blob/main/Resources/June%20rainfall%20table.png)

### December Rainfall Table

![December Rainfall Table](https://github.com/mccoycory/surfs_up/blob/main/Resources/dec%20rainfall%20table.png)
