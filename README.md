# pandas-getting-started-tutorials
Draft setup of tutorials to support the getting started pages of the Pandas documentations

## Table of Contents
1. [A DataFrame Explained](notebooks/1_table_oriented.ipynb)
1. [Load and Save DataFrames](notebooks/2_read_write.ipynb)
1. [Query DataFrames](notebooks/3_subset_data.ipynb)
1. [Plot Data](notebooks/4_plotting.ipynb)
1. [Add Columns](notebooks/5_add_columns.ipynb)
1. [Calculate Statistics](notebooks/6_calculate_statistics.ipynb)
1. [Reshape Table Layout](notebooks/7_reshape_table_layout.ipynb)
1. [Combine DataFrames](notebooks/8_combine_dataframes.ipynb)
1. [Timeseries](notebooks/9_timeseries.ipynb)
1. [Text data](notebooks/10_text_data.ipynb)

## Lesson setup notes

### Glossary

- A pandas DataFrame has columns and row indices, which are defined as column/row __labels__
- community agreed alias for pandas is `pd`
- textual data consists of strings
- one can call methods on DataFrames and Series, these methods do have parameters which are declared by method arguments (the value passed) on the function call
- DataFrames and Series do have attributes like dtypes,...

### Useful remarks on lesson setup

- Perhaps don't encourage users to jump ahead to future lessons, though in future lessons it does make sense to link back to previous lessons.
- `If you are familiar to...` pattern

### General checks to do (consistency,...)

- Use lowercase for pandas
- Use "" rather than '' quotes
- `NaN` instead of `Nan`,...
