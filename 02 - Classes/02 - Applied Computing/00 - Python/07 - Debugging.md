## Types of validation
**Syntax validation** - checks if the data conforms to a set of rules: password length, special char, num

**Range validation** - validates if data falls within a specified range

**Type validation** - checks if the data is of the correct type, such as a string, integer, or float.

| **Syntax errors** - Errors in the syntax for the given coding language.  For example, incorrect indentation in python.  These errors prevent code from compiling.                                                                                 |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <br>![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXef5UVRMc5Es7mmkOnTjsaqy-YU8XRPvlohuPhLGZLgdH_uhSkDQzWN-7BzVrDA9sIViMmZ9kCy53CwwTACcqbw2L_An_mrsvuuTMv3PXxwDLA2UxAsEXXZ52O52_ROp60KIF6Qwg?key=Ytt7FcPV5_DDDP594fKahHeT)                   |
| **Runtime Error**- Errors that occur when the code is executing.  For example, trying to call a function that does not exist.  Typically found during testing, but can be fixed with patches.                                                     |
| ![](https://lh7-rt.googleusercontent.com/docsz/AD_4nXfvJiSbcOtdlNbf0u56UpQaj1sBwudjjq5puBc9okZCOqAokaAP_6Z2b9V0Q5PMRiBKbDpj72QxO9-_3xikOcqSRRhBaFClVSu7G_7dcJ2VBesGROQF27IYDScvt7yFt-6oozBOjQ?key=Ytt7FcPV5_DDDP594fKahHeT)                       |
| **Lodgic Errors** - Errors that occur due to a fault in the logic, causing an output which is unexpected.  For example, a function returning a square root when the function was intended to return the square of a number. (*AKA* you fucked up) |
### Debugging methods
- Read through error messages - line, position type of error
- colour of code - colour of strings is different, keywords are different
- Print statements
- run smaller parts
- highlighted fuck ups
- step byu step walkthrough
- breakpoints

### Truth tables
- systematic method of testing
- useful when two conditions within statement
- use w/ trace table
- test data for testing algorithm
## Examples
![[Pasted image 20250225102437.png]]

| **b < c OR c < d**              | **a < b AND (b < c OR c < d)**                                   |
| ------------------------------- | ---------------------------------------------------------------- |
| True OR True<br>Result: True    | true AND (True OR True)<br>True AND (True)<br>Result: True       |
| True OR False<br>Result: True   | True AND (True OR False)<br>True AND (True)<br>Result: True      |
| True OR False<br>Result: True   | True AND (False OR True)<br>True AND (True)<br>Result: True      |
| True OR False:<br>Result: True  | True AND (False OR False)<br>True AND (False)<br>Result: False   |
| False OR True<br>Result: True   | False AND (True OR True)<br>False AND (True)<br>Result: False    |
| False OR True<br>Result: True   | False AND (True OR False)<br>False AND (True)<br>Result: False   |
| False OR False<br>Result: False | False AND (False OR True)<br>False AND (True)<br>Result: False   |
| False OR False<br>Result: False | False AND (False OR False)<br>False AND (False)<br>Result: False |
### Trace Tables
- Systematic method of execution
- sumulate the execution (flow of execution)


| Step | Statement       | x   | y   | Output |
| ---- | --------------- | --- | --- | ------ |
| 7    | x <- x + 8      | 16  | 4   |        |
| 8    | y <- y + 4      | 16  | 8   |        |
| 9    | While x < 32 Do | 16  | 8   |        |
| 10   | x <- x + 8      | 24  | 8   |        |
| 11   | y <- y + 4      | 24  | 12  |        |
| 12   | While x < 32 Do | 24  | 12  |        |
| 13   | x <- x + 8      | 32  | 12  |        |
| 14   | y <- y + 4      | 32  | 16  |        |
| 15   | WHILE x < 32 Do | 32  | 16  |        |
| 16   | Print x, y      | 32  | 16  | 32, 16 |
