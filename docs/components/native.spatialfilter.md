
# SPATIAL_FILTER
## Description

 This component filters an input table using a spatial predicate and a filter table.

 It generates a new table with only the rows of the input table that meet the filter criteria
 and another one with those that do not meet it.
 
## Inputs
* `Source table [Table]`: 
* `Filter table [Table]`: 
* `Geo column in source table [Column]`: 
* `Geo column in filter table [Column]`: 
* `Spatial predicate [Selection]`: 

## Outputs
* `Table with rows that pass the filter [Table]`: 
* `Table with rows that do not pass the filter [Table]`: 
