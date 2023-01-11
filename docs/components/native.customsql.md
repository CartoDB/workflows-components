
# CUSTOM_SQL_SELECT
## Description

 This component executes an arbitrary SELECT SQL statement.

 A new table will be created from the result of the entered statement

 Use $a and $b as placeholders for the input table names (you can use one, both, or none of them),
 and '$output' as placeholder for the output table name.

 The following is a valid example of code to use in this component, which will generate a new table
 with an added area column (based on a column named 'geom'), with only the rows corresponding to
 the five largest geometries:

 SELECT *, ST_AREA(geom) AS area
 FROM $a
 ORDER BY area
 LIMIT 5

 
## Inputs
* `Source table [Table]`: 
* `Source table [Table]`: 
* `SQL SELECT statement [String]`: 

## Outputs
* `Result table [Table]`: 
