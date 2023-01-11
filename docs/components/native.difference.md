
# ST_DIFFERENCE
## Description

 This component creates a new table containing the difference between the geographies
 of the input table and the combined boundary of the geographies in another table.
 That is, the part of the original geography that doesn't fall within the boundary of
 the ancillary table.

 Geographies in the secondary table must be of type polygon.

 <p><a href="https://cloud.google.com/bigquery/docs/reference/standard-sql/geography_functions#st_difference" target="_blank" rel="noopener noreferrer"> BigQuery ST_DIFFERENCE documentation</a></p>
 
## Inputs
* `Source table [Table]`: 
* `Polygons table [Table]`: 
* `Geo column in source table [Column]`: 
* `Geo column in polygons table [Column]`: 

## Outputs
* `Result table [Table]`: 
