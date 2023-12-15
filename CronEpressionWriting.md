### "<seconds><minutes><hours><day-of-month><month><day-of-week><year>"

? - only month and week can have this, Represents any arbitrary value. This can be used only in day-of-month and day-of-week fields

"*" - All. Represents that the schedule should run for every time unit.


–	Range. Represents a continuous range of values.	Using “5-8” in the <hour> field indicates the hours 5, 6, 7 and 8

,	Multiple Values. Separates a list of different values	Using “5, 6, 10” in the <hour> field indicates the hours 5, 6 and 10

/	Increment. Specifies the amount by which to increment the values of a field 
3/5 in the minute field indicates the minutes 3, 8, 13, …, 58 in an hour. */10 in the minute field indicates the minutes 0, 10, 20…, 60
