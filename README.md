>**Note**: Please **fork** the current Udacity repository so that you will have a **remote** repository in **your** Github account. Clone the remote repository to your local machine. Later, as a part of the project "Post your Work on Github", you will push your proposed changes to the remote repository in your Github account.

### Date created
This project began development on 9 September 2023 and v1.0 was published on 28 September 2023. 

### Project Title
U.S. Bikeshare Data Analysis Tool

### Description
This python script accesses, filters, and presents descriptive statistics for files containing data on U.S. bikeshare services for three American cities. It is designed as an interactive interface in order to provide a snapshot of the data contained in the files. 

### Files used
Required packages: Time, Pandas, NumPy 


Install all packages together using pip in the terminal:

```
pip install time pandas numpy
```


To install individual packages as needed:

```
pip install time

pip install pandas

pip install numpy
```
Ensure your python script begins by importing the packages required for execution:

```
import time
import pandas as pd
import numpy as np
```

Data files: 
- chicago.csv
- new_york_city.csv
- washington.csv

### Credits
https://pandas.pydata.org/docs/reference/api/pandas.DatetimeIndex.day_name.html#pandas.DatetimeIndex.day_name

https://www.geeksforgeeks.org/formatted-string-literals-f-strings-python/

https://stackoverflow.com/questions/53037698/how-can-i-find-the-most-frequent-two-column-combination-in-a-dataframe-in-python

https://www.kdnuggets.com/2019/06/select-rows-columns-pandas.html

### Update Log

v1.0: Published 28 September 2023 | Contains: 

- get_filters()
- load_data()
- time_stats()
- station_stats()
- trip_duration_stats()
- user_stats()
- data_scroller()        

v1.1: Published 29 September 2023 | Contains:

- get_filters()
- load_data()
- time_stats()
- station_stats()
- *format_duration() - Added*
- **trip_duration_stats() - Refactored**
- user_stats()
- data_scroller() 