
# ST_DUMP
## Description

 This component explodes multi-part geographies into multiple single-part ones.

 The output table has the same structure as the input one, but the geo column only contains single part geographies.
 Rows with multi-part geographies are replaced by several rows with single-part geographies and identical values for the rest of columns.
 
## Inputs
* `Source table [Table]`: 
* `Geo column [Column]`: 

## Outputs
* `Result table [Table]`: 
