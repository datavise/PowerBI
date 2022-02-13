# SWITCH

SWITCH is a great way to create buckets for data ranges, such as:



SWITCH (TRUE(),&#x20;

&#x20;   'Movies'\[Age] >= 5, "5+",

&#x20;   'Movies'\[Age] >= 3, "3+",

&#x20;   "1 to 3"                                // ELSE

)



The SWITCH statement evaluates the two conditions for TRUE values, and if neither evaluate to true, assigns them with the value of "1 to 3"









