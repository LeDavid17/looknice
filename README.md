# LookNice
Command line interface to help us migrate and format and LookML and Spark SQL code

## Commands
```looknice fix <path_to_Looker_view_file>```
Takes a Looker view file as argument and format the derived table SQL code

```looknice get-missing-descriptions <path_to_Looker_view_file>```
Takes a Looker view file as argument and returns a list of Looker dimensions with a missing description

```looknice write-lkml-schema <path_to_databricks_sql_file>```
Write the lookml code from the Databricks' SQL script

```looknice write-sql <path_to_Looker_view_file>```
Write the Databricks SQL script from the LookML view file

