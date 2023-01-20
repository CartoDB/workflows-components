
# ST_SNAPTOGRID
## Description

 This component takes an input table and creates a new one replacing its geo column by a new column
 containing the original input geography snapped to a grid a specified size (in degrees).

 Arbitrary grid sizes are not supported. The grid_size parameter is rounded so that it is of the form 10^n, where -10 < n < 0.
 
## Inputs
* `Source table [Table]`: 
* `Geo column [Column]`: 
* `Grid size (degrees) [Number]`: 

## Outputs
* `Result table [Table]`: 

## External links
[BigQuery reference](https://cloud.google.com/bigquery/docs/reference/standard-sql/geography_functions#st_snaptogrid)
      