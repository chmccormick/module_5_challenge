# module_5_challenge

##Sources used: 

 Get the duplicate mice by ID number that shows up for Mouse ID and Timepoint: 
https://www.w3schools.com/python/pandas/ref_df_duplicated.asp#:~:text=Definition%20and%20Usage,include%20when%20looking%20for%20duplicates
> df.duplicated 


Merging Two CSV Files by one specific column
https://www.geeksforgeeks.org/how-to-merge-two-csv-files-by-specific-column-using-pandas-in-python/
> .merge(how= , on=)


Using Pandas duplicated() method to retrieve duplicate mouse ID
https://www.w3schools.com/python/pandas/ref_df_duplicated.asp#:~:text=Definition%20and%20Usage,include%20when%20looking%20for%20duplicates.
> .duplicated()


Using Pandas drop_duplicates() to drop all duplicate mouse id
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.drop_duplicates.html
> .drop_duplicates()


Difference between nuniuque() and unique() (checking number of mice in clean dataframe)
https://stackoverflow.com/questions/56310788/different-outcome-using-pandas-nunique-and-unique
> .nunique()


Drop duplicates based on specific value
https://stackoverflow.com/questions/58119531/drop-duplicates-based-on-one-specific-value-pandas
> .duplicated()


Generate Summary Statistics table with .agg method()
https://stackoverflow.com/questions/57842316/pandas-calculate-variance-from-aggregation
https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.agg.html
> #.agg({'Tumor Volume (mm3)': [aggregations]})


Pandas .to_dict() to convert df to a dictionary of series or list 
https://www.geeksforgeeks.org/python-pandas-dataframe-to_dict/
> .to_dict()


Find the length of a value_counts() result
https://stackoverflow.com/questions/64234573/how-to-find-the-length-of-value-counts-that-is-greater-than-1-in-a-pandas-data
> len(df['Mouse ID'].value_counts())


Parameters of plt.pie()
https://matplotlib.org/3.1.1/api/_as_gen/matplotlib.pyplot.pie.html
> autopct= , 


Parameters of plt.bar()
https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.bar.html
> height= , 