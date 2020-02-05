pd = pandas module
df = dataframe object
s = series object

+ Read Data
  - pd.read_csv()
    - sep: character delimiter
+ Basic exploration
  - df.head() -> show first rows
  - df.tail() -> show last rows
  - df.columns -> show column names, also useful to assign new names to columns
  - df.shape -> returns tuple of dataframe dimensions
  - df.describe -> descriptive statistics of numerical columns