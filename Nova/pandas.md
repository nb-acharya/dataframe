### installation

```conda install -c conda-forge pandas```  
```pip install pandas```

# import data and export data
to_*
read_*
csv,json,sql, excel, parquet (pronounced as: paa.kay) is a open source, column oriented data storage format designed for highly efficient big data analytics and storage. Developed by apache. It is the industry standard for handling massive datasets within data lakes and data warehouses.


## PANDAS
- to explore the data, to clean the data and process the dat
- datatable is called dataframe
- it provides flexible data structure
- two primary data structure of pandas: Series(1D) and DataFrame(2D)
- pandas is a dependency of statsmodels

- Dataframe is a container for series and series is a container for scalar.
- Mutability: columns can be added and removed but length of the series is immutable. you can't take one existing column (Series) and shrink or grow just that column while it stays attached to the DataFrame — every column must stay the same length as the DataFrame's index, since they all share it.

### Benefits
- easy handling of missing data(represented as NaN)
- size mutability: columns can be inserted and deleted from DataFrame






