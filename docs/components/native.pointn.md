
# ST_POINTN
## Description

 This component adds a new column
 with the point at the n-th position in the original input geography.

 The geography must be of type linestring.

 It will set the column value to null if the original geography is not a linestring, if it is empty,
 or if there is no vertex at the given index.
 
## Inputs
* `Source table [Table]`: 
* `Geo column [Column]`: 
* `Point index [Number]`: 

## Outputs
* `Result table [Table]`: 

## External links
[BigQuery reference](https://cloud.google.com/bigquery/docs/reference/standard-sql/geography_functions#st_pointn)
      