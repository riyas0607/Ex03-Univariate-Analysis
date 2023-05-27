# Ex03-Univariate-Analysis
# Aim
To read the given dataset and perform univariate analysis.
Explanation
Univariate analysis is basically the simplest form to analyze data. Uni means one and this means
that the data has only one kind of variable. The major reason for univariate analysis is to use the
data to describe. The analysis will take data, summarise it, and then find some pattern in the data.
# Algorithm
Step1 Read the given data.
Step2 Get the information about the data.
Step3 Remove the null values from the data.
Step4 Mention the datatypes from the data.
Step5 Count the values from the data.
Step6 Do plots like boxplots,countplot,distribution plot,histogram plot.
# Program
Developed by:KUMARAVEL R

Register Number:212221220029

```
import pandas as pd
import numpy as np
import seaborn as sns
df=pd.read_csv("SuperStore.csv")
print(df)
df.info()
df.describe()
df.isnull().sum()
df.dtypes
df['Row ID'].value_counts()
sns.boxplot(x="Row ID", data=df)
sns.countplot(x="Row ID", data=df)
sns.distplot(df["Row ID"])
sns.histplot(x="Row ID", data=df)
```
# Output
Dataset

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/1.jpg)

Dataset info

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/2.jpg)



Dataset describe

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/3.jpg)


Null value

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/4.jpg)

Data types

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/5.jpg)

Value count

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/6.jpg)

Boxplot

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/7.jpg)

Count plot

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/8.jpg)

Distribution plot

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/9.jpg)

Histogram plot

![](https://github.com/KumaravelIT/Ex03-Univariate-Analysis/blob/main/99.jpg)


# Result
Thus we have read the given data and performed the univariate analysis with different types of
plots.
