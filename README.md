To fill the outcome cell with a different color, depending on the associated outcome, use the manage rule in condition formatting to add multiple rules at the same time.  

<img width="540" alt="1" src="https://github.com/Glowary/excel-challenge/assets/141696007/6b0c2563-786e-4c07-91a6-94f35b8daaee">  

To find percent funded that uses the formula
`=[@pledged]/[@goal]%`  

Three-Color Scale  

<img width="540" alt="2" src="https://github.com/Glowary/excel-challenge/assets/141696007/951a50f0-dc2c-4bb0-9fe5-1261c6f2ac3b">  

To find the average donation use a formula with iferror when divided by zero
`=iferror([@pledged]/[@[backers_count]],0)`

Create Two Columns from One  
<img width="540" alt="3" src="https://github.com/Glowary/excel-challenge/assets/141696007/9189e877-4e96-4e41-870b-a83390d12991">  

Create Pivot Tables and Graphs  

<img width="296" alt="4" src="https://github.com/Glowary/excel-challenge/assets/141696007/5e5d7659-2f09-46f4-82a9-19354f063669">
<img width="290" alt="5" src="https://github.com/Glowary/excel-challenge/assets/141696007/45e836bd-cfc1-473a-8a1a-18a64033ebfd">  

To convert Unix timestamps to normal dates use formula
`=((([COLUMN]]/60)/60)/24)+DATE(1970,1,1)`

To count projects created with goals within the ranges listed above
`=COUNTIFS(Table1[goal],"<1000",Table1[outcome],"=successful")`

To find the percentage of projects within the range, take the number from the corresponding outcome cell and divide it by the total number of projects.

Formulas For Evaluating Valuation  

```=AVERAGE(DATA)
=MEDIAN(DATA)
=MIN(DATA)
=MAX(DATA)
=VAR(DATA)
=STDEV(DATA)
