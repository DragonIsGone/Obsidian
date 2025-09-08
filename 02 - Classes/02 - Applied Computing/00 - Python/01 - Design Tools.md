---
tags:
  - computing
---
**[[00 - Applied Computing Study Design.docx]]
## IPO Charts
>IPO Charts are essentially used to effectively communicate code function with clients
- IPO (Input -> Process -> Output)
- AKA "IPO model" or "IPO diagram"
- IPO charts are a visual tool to describe a workflow / the flow of information through a system/subsystem
- IPO charts help identify influences on processes and how they effect outcomes
### INPUT
- Data
- Information
- Resources
### PROCESS
- Activities
- Transformations
- operations
### OUPUT
- results
- products 
- outcomes
-----------------
### Example:
>Example of an IPO chart in a manufacturing plant
![[IPO Example in manufacition.png]]

## Flowchart
>Flow charts are also used in many fields to easily convey decision making, both human and code
- Flowcharts used for algorithm visualisation
- identifies flows
- graphical representation of code logic
### Flow Chart Symbols

![[Flowchart Table 1 of 5.png]]
- Start/End are known as terminator represents start and end
- flow show direction of code/algo

![[Flowchart Table 2 of 5.png]]
- Process are the "action" of code
- Decision indicated a question (yes/no)

![[Flowchart Table 3 of 5.png]]
- Data is representation of in and out inputs
- database is housed service for storage

![[Flowchart Table 4 of 5.png]]
- Manual input represents things like keyboard strokes used in things like login
- Manual operation is something done manually (no shit)

![[Flowchart Table 5 of 5.png]]
- Document is an input or output like emails/orders
- Display, sent to end user screen
### Practice flowchart:
**Create flowchart for PSUEDOCODE**
````
START

INPUT integer
INPUT integerB

C ← A + B

DISPLAY C

END
````

![[Practice Flowchart.png]]
![[Practice Flowchart 2.png]]

## PSEUDOCODE
- Way to describe code functions
- Universal for all language
- Focus on logic and steps rather that syntax
### Unofficial Rules
- Assigning values to variables needs a backward arrow <--
- Equal sign (=) is used to compare
	>IF B = O
- Keywords should be capitalised
	- IF
	- THEN
	- ELSE
	- ENDIF
- Indentation is important in PC (like python)
- **INPUT** Is used to retrieve data
- **READ** is used to retrieve data from base/file
- **PRINT** or **DISPLAY** used to show user ==(Be consistent)==
- Naming Conventions:
	- Camel Case - pokemonType, pokemonHealth, pokemonAbility
	- Hungarian notation - strPokemonType
### PSEUDOCODE Example
````
START

INPUT size

INPUT pepperoni

order ← size + " " + pepperoni

PRINT "Your pizza is on the way"

END
````


