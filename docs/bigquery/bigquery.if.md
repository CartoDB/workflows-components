
# IF
## Description

 This component represents a conditional statement.

 It takes a condition table, a secondary table and a condition.
 If the condition is true for the condition table, the secondary table 'passes' through the component,
 and it will be available for other components further in the workflow. Otherwise, those components
 will not be executed.

 The condition is verified for all rows in the input table and must be true for all of them.
 
## Inputs
* `Condition table [Table]`: 
* `Table to use [Table]`: 
* `Conditional expression [String]`: 

## Outputs
* `Result table [Table]`: 
