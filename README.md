Descriptive Statistics with Python Project
Descriptive Statistics is the subject matter of this project. 
Descriptive statistics gives us the basic summary measures about the dataset. The summary measures include measures of central tendency (mean, median and mode) and measures of variability (variance, standard deviation, minimum/maximum values, IQR (Interquartile Range), skewness and kurtosis). I have used the fortune 500 dataset from the data world website for this project.

Table of Contents
Introduction to descriptive statistics
Measures of central tendency
Mean
Median
Mode
Measures of dispersion
Variance
Standard deviation
Coefficient of variation
IQR (Interquartile range)
Skewness
Kurtosis
Dataset description
Import libraries
Import dataset
Exploratory data analysis
Descriptive statistics with describe() function
Summary statistics of numerical columns
Summary statistics of character columns
Summary statistics of all the columns
Computation of measures of central tendency
Mean
Median
Mode
Computation of measures of dispersion or variability
Minimum and maximum values
Range
Variance
Standard deviation
Median
Interquartile Range
Computation of measures of shape of distribution
Skewness
Kurtosis
Results and conclusion


1. Introduction to descriptive statistics
Descriptive statistics are numbers that are used to describe and summarize the data. They are used to describe the basic features of the data under consideration. They provide simple summary measures which give an overview of the dataset. Summary measures that are commonly used to describe a data set are measures of central tendency and measures of variability or dispersion.

Measures of central tendency include the mean, median and mode. These measures summarize a given data set by providing a single data point. These measures describe the center position of a distribution for a data set. We analyze the frequency of each data point in the distribution and describes it using the mean, median or mode. They provide the average of a data set. They can be either a representation of entire population or a sample of the population.

Measures of variability or dispersion include the variance or standard deviation, coefficient of variation, minimum and maximum values, IQR (Interquartile Range), skewness andkurtosis`. These measures help us to analyze how spread-out the distribution is for a dataset. So, they provide the shape of the data set.

2. Measures of central tendency
Central tendency means a central value which describe a probability distribution. It may also be called a center or location of the distribution. The most common measures of central tendency are mean, median and mode. The most common measure of central tendency is the mean. For skewed distribution or when there is concern about outliers, the median may be preferred. So, median is more robust measure than the mean.

Mean
The most common measure of central tendency is the mean.
Mean is also known as the simple average.
It is denoted by greek letter µ for population and by ¯x for sample.
We can find mean of a number of elements by adding all the elements in a dataset and then dividing by the number of elements in the dataset.
It is the most common measure of central tendency but it has a drawback.
The mean is affected by the presence of outliers.
So, mean alone is not enough for making business decisions.
Median
Median is the number which divides the dataset into two equal halves.
To calculate the median, we have to arrange our dataset of n numbers in ascending order.
The median of this dataset is the number at (n+1)/2 th position, if n is odd.
If n is even, then the median is the average of the (n/2)th number and (n+2)/2 th number.
Median is robust to outliers.
So, for skewed distribution or when there is concern about outliers, the median may be preferred.
Mode
Mode of a dataset is the value that occurs most often in the dataset.
Mode is the value that has the highest frequency of occurrence in the dataset.
There is no best measure that give us the complete picture. So, these measures of central tendency (mean, median and mode) should be used together to represent the full picture.

3. Measures of dispersion or variability
Dispersion is an indicator of how far away from the center, we can find the data values. The most common measures of dispersion are variance, standard deviation and interquartile range (IQR). Variance is the standard measure of spread. The standard deviation is the square root of the variance. The variance and standard deviation are two useful measures of spread.

Variance
Variance measures the dispersion of a set of data points around their mean value.
It is the mean of the squares of the individual deviations.
Variance gives results in the original units squared.
Standard deviation
Standard deviation is the most common used measure of variability.
It is the square-root of the variance.
For Normally distributed data, approximately 95% of the values lie within 2 s.d. of the mean.
Standard deviation gives results in the original units.
Coefficient of Variation (CV)
Coefficient of Variation (CV) is equal to the standard deviation divided by the mean.
It is also known as relative standard deviation.
IQR (Interquartile range)
A third measure of spread is the interquartile range (IQR).
The IQR is calculated using the boundaries of data situated between the 1st and the 3rd quartiles.
The interquartile range (IQR) can be calculated as follows:- IQR = Q3 – Q1
In the same way that the median is more robust than the mean, the IQR is a more robust measure of spread than variance and standard deviation and should therefore be preferred for small or asymmetrical distributions.
It is a robust measure of spread.
Measures of shape
Now, we will take a look at measures of shape of distribution. There are two statistical measures that can tell us about the shape of the distribution. These measures are skewness and kurtosis. These measures can be used to convey information about the shape of the distribution of the dataset.

Skewness
Skewness is a measure of a distribution's symmetry or more precisely lack of symmetry.
It is used to mean the absence of symmetry from the mean of the dataset.
It is a characteristic of the deviation from the mean.
It is used to indicate the shape of the distribution of data.
Negative skewness
Negative values for skewness indicate negative skewness.
In this case, the data are skewed or tail to left.
By skewed left, we mean that the left tail is long relative to the right tail.
The data values may extend further to the left but concentrated in the right.
So, there is a long tail and distortion is caused by extremely small values which pull the mean downward so that it is less than the median.
Hence, in this case we have Mean < Median < Mode
Zero skewness
Zero skewness means skewness value of zero.
It means the dataset is symmetrical.
A data set is symmetrical if it looks the same to the left and right to the center point.
The dataset looks bell shaped or symmetrical.
A perfectly symmetrical data set will have a skewness of zero.
So, the normal distribution which is perfectly symmetrical has a skewness of 0.
So, in this case, we have Mean = Median = Mode
Positive skewness
Positive values for skewness indicate positive skewness.
The dataset are skewed or tail to right.
By skewed right, we mean that the right tail is long relative to the left tail.
The data values are concentrated in the right.
So, there is a long tail to the right that is caused by extremely large values which pull the mean upward so that it is greater than the median.
So, we have Mean > Median > Mode
Reference range on skewness values
The rule of thumb for skewness values are:

If the skewness is between -0.5 and 0.5, the data are fairly symmetrical.
If the skewness is between -1 and – 0.5 or between 0.5 and 1, the data are moderately skewed.
If the skewness is less than -1 or greater than 1, the data are highly skewed.
Kurtosis
Kurtosis is the degree of peakedness of a distribution.
Data sets with high kurtosis tend to have a distinct peak near the mean, decline rather rapidly and have heavy tails.
Data sets with low kurtosis tend to have a flat top near the mean rather than a sharp peak.
Reference range for kurtosis
The reference standard is a normal distribution, which has a kurtosis of 3.
Often, excess kurtosis is presented instead of kurtosis, where excess kurtosis is simply kurtosis - 3.
Mesokurtic curve
A normal distribution has kurtosis exactly 3 (excess kurtosis exactly 0).
Any distribution with kurtosis ≈3 (excess ≈ 0) is called mesokurtic.
Platykurtic curve
A distribution with kurtosis < 3 (excess kurtosis < 0) is called platykurtic.
As compared to a normal distribution, its central peak is lower and broader, and its tails are shorter and thinner.
Leptokurtic curve
A distribution with kurtosis > 3 (excess kurtosis > 0) is called leptokurtic.
As compared to a normal distribution, its central peak is higher and sharper, and its tails are longer and fatter.
Summary
So far, we have looked at the measures of central tendency of the data which include mean, median and mode. Also, we have taken a look at measures of spread of the data which consists of variance, standard deviation, interquartile range (IQR), minimum and maximum values. We have also discussed skewness and kurtosis as measures of shape. These quantities can only be used for quantitative variables not for categorical variables.

4. Dataset description
I have used the fortune 500 dataset for this project. I have downloaded this dataset from the data world website. This data set can be downloaded from the following url –

https://data.world/alexandra/fortune-500

The data set consists of revenue and profit figures of fortune 500 companies along with their rank.

5. Import libraries
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline
Ignore warnings
import warnings
warnings.filterwarnings('ignore')
6. Import dataset
data = 'C:/datasets/fortune500.csv'

df = pd.read_csv(data)
7. Exploratory data analysis
Now, I will explore the data to gain insights about the data.

View dimensions of dataset
df.shape
(25500, 5)
We can see that there are 25500 instances and 5 variables in the data set.

Preview the dataset
df.head()
Year	Rank	Company	Revenue (in millions)	Profit (in millions)
0	1955	1	General Motors	9823.5	806
1	1955	2	Exxon Mobil	5661.4	584.8
2	1955	3	U.S. Steel	3250.4	195.4
3	1955	4	General Electric	2959.1	212.6
4	1955	5	Esmark	2510.8	19.1
View summary of dataset
df.info()
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 25500 entries, 0 to 25499
Data columns (total 5 columns):
Year                     25500 non-null int64
Rank                     25500 non-null int64
Company                  25500 non-null object
Revenue (in millions)    25500 non-null float64
Profit (in millions)     25500 non-null object
dtypes: float64(1), int64(2), object(2)
memory usage: 996.2+ KB
Observations
We can see that the Year and Rank variables have integer data types as expected. The Company variable is of object data type.

The Revenue (in millions) variable is of float data type.

The Profit (in millions) variable is of object data type.

Check for missing values
df.isnull().sum()
Year                     0
Rank                     0
Company                  0
Revenue (in millions)    0
Profit (in millions)     0
dtype: int64
The above command shows that there are no missing values in the dataset.

8. Descriptive statistics with describe() function
Descriptive or summary statistics in python – pandas, can be obtained by using the describe() function. The describe() function gives us the count, mean, standard deviation(std), minimum, Q1(25%), median(50%), Q3(75%), IQR(Q3 - Q1) and maximum values.

I will demonstrate the usage of describe() function as follows.

Summary statistics of numerical columns
df.describe()
Year	Rank	Revenue (in millions)
count	25500.00000	25500.000000	25500.000000
mean	1980.00000	250.499765	4273.329635
std	14.71989	144.339963	11351.884979
min	1955.00000	1.000000	49.700000
25%	1967.00000	125.750000	362.300000
50%	1980.00000	250.500000	1019.000000
75%	1993.00000	375.250000	3871.000000
max	2005.00000	500.000000	288189.000000
We can see that the describe() function excludes the character columns and gives summary statistics of numeric columns only.

Summary statistics of character columns
The describe() function with an argument named include along with value object(include='object') gives the summary statistics of the character columns.
df.describe(include=['object'])
Company	Profit (in millions)
count	25500	25500
unique	1887	6977
top	CBS	N.A.
freq	57	369
Summary statistics of all the columns
The describe() function with include='all' gives the summary statistics of all the columns.
We need to add a variable named include='all' to get the summary statistics or descriptive statistics of both numeric and character columns.
df.describe(include='all')
Year	Rank	Company	Revenue (in millions)	Profit (in millions)
count	25500.00000	25500.000000	25500	25500.000000	25500
unique	NaN	NaN	1887	NaN	6977
top	NaN	NaN	CBS	NaN	N.A.
freq	NaN	NaN	57	NaN	369
mean	1980.00000	250.499765	NaN	4273.329635	NaN
std	14.71989	144.339963	NaN	11351.884979	NaN
min	1955.00000	1.000000	NaN	49.700000	NaN
25%	1967.00000	125.750000	NaN	362.300000	NaN
50%	1980.00000	250.500000	NaN	1019.000000	NaN
75%	1993.00000	375.250000	NaN	3871.000000	NaN
max	2005.00000	500.000000	NaN	288189.000000	NaN
9. Computation of measures of central tendency
In this section, I will compute the measures of central tendency - mean, median and mode.

These statistics give us a approximate value of the middle of a numeric variable.

I will use the Revenue (in millions) variable for calculations.

Mean
mean = df['Revenue (in millions)'].mean()

print(mean)
4273.32963529412
Median
median = df['Revenue (in millions)'].median()

print(median)
1019.0
Mode
mode = df['Revenue (in millions)'].mode()

print(mode)
0    85.0
1    86.2
2    90.0
dtype: float64
Observation
We can see that mean > median > mode. So, the distribution of Revenue (in millions) is positively skewed. I will plot its distribution to confirm the same.
Plot the distribution
data = df['Revenue (in millions)']

sns.distplot(data, bins=10, hist=True, kde=True, label = 'Revenue (in millions)')
<matplotlib.axes._subplots.AxesSubplot at 0xb0caa9b38>

The above plot confirms that the Revenue (in millions) is positively skewed.

10. Computation of measures of dispersion or variability
In this section, I will compute the measures of dispersion or variability - minimum and maximum values, range, variance, standard-deviation, IQR.

Again, I will use the Revenue (in millions) variable for calculations.

Minimum value
df['Revenue (in millions)'].min()
49.7
Maximum value
df['Revenue (in millions)'].max()
288189.0
Range
df['Revenue (in millions)'].max() - df['Revenue (in millions)'].min()
288139.3
Variance
df['Revenue (in millions)'].var()
128865292.56794235
Standard deviation
df['Revenue (in millions)'].std()
11351.88497862546
Median (Q2 or 50th percentile)
Q2 = df['Revenue (in millions)'].quantile(0.5)

Q2
1019.0
Q3 or 75th percentile
Q3 = df['Revenue (in millions)'].quantile(0.75)

Q3
3871.0
Q1 or 25th percentile
Q1 = df['Revenue (in millions)'].quantile(0.25)

Q1
362.3
Interquartile Range
IQR = Q3  - Q1

IQR
3508.7
Draw boxplot
plt.boxplot(df['Revenue (in millions)'])

plt.show()

11. Computation of measures of shape of distribution
In this section, I will compute the measures of shape of distribution - skewness and kurtosis.

Again, I will use the Revenue (in millions) variable for calculations.

Skewness
df['Revenue (in millions)'].skew()
9.32673729580641
Interpretation
I find the skewness to be 9.3267. So, it is greater than 1. Hence, we can conclude that the Revenue (in millions) data is highly skewed.

Kurtosis
df['Revenue (in millions)'].kurt()
132.04561027793167
Interpretation
I find the kurtosis to be 132.0456. So, it is greater than 3 and so excess kurtosis > 0. Hence, we can conclude that the Revenue (in millions) curve is a leptokurtic curve. As compared to a normal distribution, its central peak is higher and sharper, and its tails are longer and fatter.

12. Results and conclusion
In this project, I describe the descriptive statistics that are used to summarize a dataset.
In particular, I have described the measures of central tendency (mean, median and mode). I have also described the measures of dispersion or variability (variance, standard deviation, coefficient of variation, minimum and maximum values, IQR) and measures of shape (skewness and kurtosis).
I have demonstrated how to calculate the summary statistics with describe() function.
I have computed the measures of central tendency-mean, median and mode for the Revenue (in millions)variable. I have found mean > median > mode. So, the distribution of Revenue (in millions) is positively skewed. I have plotted its distribution to confirm the same.
I have computed the measures of dispersion or variability-range, variance, standard-deviation, median and IQR for the Revenue (in millions)variable.
I have also computed the measures of shape-skewness and kurtosis for the Revenue (in millions)variable.
I find the skewness to be 9.3267. So, it is greater than 1. Hence, we can conclude that the Revenue (in millions) data is highly skewed.
I find the kurtosis to be 132.0456. So, it is greater than 3 and so excess kurtosis > 0. Hence, we can conclude that the Revenue (in millions) curve is a leptokurtic curve. As compared to a normal distribution, its central peak is higher and sharper, and its tails are longer and fatter.
