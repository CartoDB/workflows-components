
# CALL_PROCEDURE
## Description

 This component executes an arbitrary CALL SQL statement.

 Use $a and $b as placeholders for the input table names (you can use one, both, or none of them),
 and '$output' as placeholder for the output table name.

 The procedure that you are calling is responsible of creating the output table in the path stored
 in the '$output' variable.

 The following is a valid example of code to use in this component:

 CALL MY_PROCEDURE($a, 10, $output);

 
## Inputs
* `Source table [Table]`: 
* `Source table [Table]`: 
* `SQL CALL statement [String]`: 

## Outputs
* `Result table [Table]`: 
