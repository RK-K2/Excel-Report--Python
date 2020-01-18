# Excel-Report--Python

### Basic Excel reporting using Python Pandas and Numpy

We receive multiple feeds from different vendors and like to see if all the files that received were within SLA. 
 We can determine if the vendor met the SLA by comparing the Input arrival time and SLA time. 
This notebook will compare the Input arrival time and SLA time and create a new column SLA-CHECK with "Y"/"N."
For easy identification and reporting, the column can be color coded. The same details can be exported to excel and share with the stakeholders.

### Following Libraries used:
Pandas -> For reading excel 
numpy -> For condition 
