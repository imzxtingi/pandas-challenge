# pandas-challenge
Module 4 - PyCitySchools

I used StackOverflow and geeksforgeeks.org to look up the difference between .count() and .size() because initially when I was performing the groupby with .count() it provided me with a DataFrame that wasn't properly formatting when making the per_school_summary DataFrame, so I looked up what could provide just a single number instead of a DataFrame and found .size() is applied to a Series instead of a DataFrame.

Also in this line of code "pd.cut(school_spending_df["Per Student Budget"].str[1:].astype(float)" I found it through StackOverflow because I was getting an error when trying to create bins for school spending.  It was telling me that (TypeError: '<' not supported between instances of 'int' and 'str') so I found an answer to help me change the type from string to float.  
