# Date Functions

Either use a string manipulation function like RIGHT():

Month Year = RIGHT("0" & 'Date (Order)'\[Month Number of Year], 2)





Or use the FORMAT function to format the column as a date:

Month Year Format = FORMAT('Date (Order)'\[Date], "MM-YYYY")











