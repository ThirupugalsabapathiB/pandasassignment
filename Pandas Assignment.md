# PandasAssignment

Q1. How do you load a CSV file into a Pandas DataFrame?
    Ans:Firstly,Import Pandas library
        Secondly,copy the link of file you want to load that should be in csv file format
        Thirdly,DataFrame=pd.read_csv "link"
        And call the DataFrame.

Q2. How do you check the data type of a column in a Pandas DataFrame?
    Ans:By using dtypes
        Ex:df.dtypes

Q3. How do you select rows from a Pandas DataFrame based on a condition?
    Ans:

Q4. How do you rename columns in a Pandas DataFrame?
    Ans:By using
        df['new column']

Q5. How do you drop columns in a Pandas DataFrame?
    Ans:

Q6. How do you find the unique values in a column of a Pandas DataFrame?
    Ans:By using unique()function
        df['column name']unique()

Q7. How do you find the number of missing values in each column of a Pandas DataFrame?
    Ans:To find missing values in dataframe
        df['column name'].isnull().sum()

Q8. How do you fill missing values in a Pandas DataFrame with a specific value?
    Ans:using replace() function

Q9. How do you concatenate two Pandas DataFrames?
    Ans:using concat operation
        dfconcat=[df1,df2]
        result=pd.concat(dfconcat)
        result

Q10. How do you merge two Pandas DataFrames on a specific column?
    Ans:df['new column']=df1['firstpandacolumn']+df2['secondpandacolumn']

Q11. How do you group data in a Pandas DataFrame by a specific column and apply an aggregation function?
    Ans:Using groupby()
        And to aggregate functions like sum(),count() etc...

Q12. How do you pivot a Pandas DataFrame?
    Ans:pivot() fn is used to reshape a Dataframe organized by given Index
        Also we can use set.Index

Q13. How do you change the data type of a column in a Pandas DataFrame?

Q14. How do you sort a Pandas DataFrame by a specific column?

Q15. How do you create a copy of a Pandas DataFrame?
    Ans:Using copy()
        Although,The changes do not occur in copied dataframe,
        If original dataframe is changed.

Q16. How do you filter rows of a Pandas DataFrame by multiple conditions?

Q17. How do you calculate the mean of a column in a Pandas DataFrame?
    Ans:Using Dataframe.mean() axis=0 to calculate column wise.

Q18. How do you calculate the standard deviation of a column in a Pandas DataFrame?
    Ans:Using describe()
        df.describe() to find standard deviation.

Q19. How do you calculate the correlation between two columns in a Pandas DataFrame?
    Ans:correlate column1 & column2
        df[col1].corr(df[col2])
        corr.

Q20. How do you select specific columns in a DataFrame using their labels?
    Ans:To select the specific column
        putting string name of column in brackets
        Ex:df['name']

Q21. How do you select specific rows in a DataFrame using their indexes?
    Ans:select specific row by Integer Index
        Using df.iloc[n]
        n=Refers to the row selected.

Q22. How do you sort a DataFrame by a specific column?
    Ans:Using sort()
    
Q23. How do you create a new column in a DataFrame based on the values of another column?
    Ans:df['newcolumn']=df['name']+df['age']

Q24. How do you remove duplicates from a DataFrame?
    Ans:drop_duplicates() function is used

Q25. What is the difference between .loc and .iloc in Pandas?
    Ans:.loc-gets rows & columns with particular labels.
        .iloc-gets rows and columns at integer locations.
