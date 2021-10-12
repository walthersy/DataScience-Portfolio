[<img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white">](https://www.linkedin.com/in/walthersy/)


# Data Science Portfolio

Language used: <img src="https://upload.wikimedia.org/wikipedia/commons/c/c3/Python-logo-notext.svg" width=20>



## Portfolio 1  :bicyclist:

Portfolio 1 is about exploring a cyclist's 2016 and 2019 cycling and time trial races.

In this notebook, I have explored the speed data particularly as it is the most crucial variable in a race and have done the necessary cleaning. Afterwhich, I have considered other variables in relation to speed, such as elevation gain, development, and gear usage.

Interestingly, I have also recommended how Steve can potentially increase his race speed after analysing the data.

_The data files come from [Strava](https://www.strava.com/) and are loaded by a custom function_.

```
from gpxutils import parse_gpx 
```

`parse_gpx` is then used in the ff way:
```
parse_gpx('files/Calga_RR_2016.gpx')
```
  
  
## Portfolio 2  :soccer:


Portfolio 2 is about examining the sports vouchers program in __South Australia__ 🦘 and whether it is beneficial to more affluent families.

Specifically, I checked the relationship between some [ABS SEIFA data by LGA](http://stat.data.abs.gov.au/Index.aspx?DataSetCode=ABS_SEIFA_LGA#) and voucher activities.

I have also done some data transformations and explored the data to see which sports and LGAs standout and whether SEIFA score have something to do with voucher activities.

A similar analysis has also been done for Queensland's sports vouchers program.


## Portfolio 3  :phone:

Portfolio 3 is about the _process_ of building a predictive model for analysing customer churn from a range of data that was generated (by [Hume Winzar](https://www.linkedin.com/in/humewinzar/) from Macquarie University) based on a real dataset provided by __Optus__. The data is simulated but the column headings are the same.

For the predictive model, I have used a Logistic Regression to predict customer churn and have achieved an accuracy score of about 72.85% after eliminating features that have less predictive power. A recursive feature elimination (RFE) method was used to reduce features.
