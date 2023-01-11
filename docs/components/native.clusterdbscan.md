
# ST_CLUSTERDBSCAN
## Description

 This component performs a DB Scan clustering.
 Given an input table and a geo column, it creates a new table with the same content as the input one
 and an additional column named 'cluster' containing the cluster id corresponding to each geography.

 <p><a href="https://cloud.google.com/bigquery/docs/reference/standard-sql/geography_functions#st_clusterdbscan" target="_blank" rel="noopener noreferrer"> BigQuery ST_CLUSTERDBSCAN documentation</a></p>
 
## Inputs
* `Source table [Table]`: 
* `Geo column [Column]`: 
* `Search radius (m) [Number]`: 
* `Minimum number of geographies [Number]`: 

## Outputs
* `Result table [Table]`: 
