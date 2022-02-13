# CALCULATE

CALCULATE can be used to overwrite or change the existing filter context.



Imagine we wanted to create a measure that contained the total budget for all movies:



`Total Budget = CALCULATE([budget],`&#x20;

`ALL('movies'[title])`

`)`

We could then work out a contribution % for each movie's budget to the overall budget:



`DIVIDE('movies'[budget], [Total Budget])`





