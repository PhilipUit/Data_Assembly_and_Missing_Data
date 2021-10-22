# Data_Assembly_and_Missing_Data
Using Data Assembly to Tidy Data, Add rows, Add columns, and Merge Data. Using Missing Data strategies to find &amp; deal with missing data, use sklearn, SimpleImputer, import modules, joins/merge dataframes, and concat tables based on unique identifiers. Source: https://github.com/chendaniely/pandas_for_everyone/tree/master/data
## 1. Chapter 4 - Data Assembly
## 1.1 Tidy Data
""" The idea of "Tidy Data" comes from RStudio developer Hadley Wickham in an article by the same name, published in 2014 by the Journal of Statistical Software. Wickham defined a "framework" set of 3 characteristics that all "tidy," or easily analyzable, data share (Tidy Data, Section 2.3):

Each variable forms a column. Each observation forms a row. Each type of observational unit forms a table. Wickham makes the observation that his three rules correspond to Edgar F. Codd's 3rd Normal Form (3NF) that forms the backbone of relational database design. We'll discuss relevant parts of 3NF in Section 1.3 below, and look at Tidy Data in more detail as we discuss Exploratory Data Analysis.

#### Reference
Wickham, H. (2014). Tidy data. Journal of Statistical Software, 59(10), 1-23."

## 1.2 Adding Rows
"Section 4.3.1 discusses adding (concatenating) rows from three dataframes with identical column names, adding a series to a dataframe as well as converting the series to a dataframe before adding, and finally, adding dataframes while ignoring the indexes so numbering is continuous."

Some examples follow. Notice we made slight changes in the file naming to be able to work on this program from the source: https://github.com/chendaniely/pandas_for_everyone/tree/master/data

Source: https://github.com/chendaniely/pandas_for_everyone/tree/master/data
## 2.2 Finding and Dealing with missing data
Demonstrate several of dataframe merges from: Chrisalbon Import Modules
Import Modules
data source: https://chrisalbon.com/python/data_wrangling/pandas_join_merge_dataframe/
