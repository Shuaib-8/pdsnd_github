### Date created
created the project and README file on: 26/09/2018

### Project Title
**Explore US Bike Share Data**

### Description
In this project, I made use of Python to explore data related to bike share systems for three major cities in the US — Chicago, New York City (NYC), and Washington. I assembled code from imported data to answer interesting questions by computing descriptive statistics. I constructed a Python script that takes in raw input to create an interactive experience when launched in the terminal to present these findings.

**Datasets**

Randomly chosen data for these three cities is provided for the first six month month of 2017 - all of these data files contain six columns:

Start time | End time | Trip Duration | Start Station | End Station | User type |
------------ | ------------- | ------------- | ------------- | ------------- | ------------ |
(e.g., 2017-01-01 00:07:57) | (e.g., 2017-01-01 00:20:53) | in seconds - (e.g., 776) | (e.g., Broadway & Barry Ave) | (e.g., Sedgwick St & North Ave) | (Subscriber or Customer)


The Chicago and New York City files also have the following two columns:

Gender | Birth year
--- | --- |
Male/Female | YY-MM-DD

**Statistics computed**

Code was written to provide the following information:

1) *Popular travel times*

* most common month
*  most common day of week
* most common hour of day

2) *Popular stations and trip*

* most common start station
* most common end station
* most common trip from start to end (i.e., most frequent combination of start station and end station)

3) *Trip duration*

* Total ```(SUM)``` travel time
* Average ```(MEAN/AVG)``` travel time

4) *User info*

* counts of each user type
* counts of each gender (only available for NYC and Chicago)
* earliest, most recent, most common year of birth (only available for NYC and Chicago)


### Files used
The data I used is provided by Motivate, a bike share system provider for many major cities in the United States, to uncover bike share usage patterns.

 If you want to see the original files, they can be accessed here:
 - [Chicago]https://www.divvybikes.com/system-data - {chicago.csv}
 - [NYC]https://www.citibikenyc.com/system-data - {new_york_city.csv}
 - [Washington]https://www.capitalbikeshare.com/system-data - {washington.csv}

### Credits
Credit also to Udacity for cleaning (wrangling) the data, as they are much larger and messier; also allowing me to practice my data analysis skills more easily/coherently by condensing the data into six columns.

The references I used for the project to make the experience for the user interactive/accessible include:

- https://stackoverflow.com/questions/23294658/asking-the-user-for-input-until-they-give-a-valid-response - used for configuring the while loop for implementing validation rules.

- https://www.youtube.com/watch?v=yCgJGsg0Xa4&t=197s - working with dates and times in pandas.

- https://stackoverflow.com/questions/10202570/pandas-dataframe-find-row-where-values-for-column-is-maximal - finding rows alongside the columns’s maximum value
OR
 https://s3.amazonaws.com/assets.datacamp.com/production/course_2566/slides/ch5_slides.pdf - manipulating data frames with pandas

- https://www.reddit.com/r/learnpython/comments/7s99rk/pandas_sort_by_most_frequent_value_combinations/ - sort by most frequent value combinations
