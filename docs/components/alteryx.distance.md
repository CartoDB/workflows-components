
# Distance
## Description

 This component calculates the minimum distance between geographies of an input table and those of a second table.

 It generates a new table with the same content as the main input table, plus two new column: 'nearest_id' and 'nearest_distance'.
 
## Inputs
* `Source table [Table]`: 
* `Point or centroid source [Column]`: 
* `Point, line or polygon destination  [Column]`: 
* `When a point is inside a polygon [Selection]`: 
* `Create nearest interior point inside of the polygon [Boolean]`: 
* `Output direction in degrees [Boolean]`: 
* `Output cardinal direction [Boolean]`: 
* `Units [Selection]`: 

## Outputs
* `Result table [Table]`: 

## External links
[BigQuery reference](https://cloud.google.com/bigquery/docs/reference/standard-sql/geography_functions#st_distance)
      