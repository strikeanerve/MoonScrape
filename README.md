# ** MoonScrape **

This web scraper allows you to grab times of moon phases for a specified duration and output those times to a csv file. This includes the new, first quarter, full and last quarter moon phases.

## ** Example: **

In Line 46, edit the startdate function's arguments: (startmonth, startyear, endmonth, endyear


`startdate('January', '2016', 'December', '2017')`

In the example, this function collects all data starting in Jan 2016 through Dec 2017.

This will output a csv file with the Day, Month, Year, Time in UTC, and type of moon phase that occurs for a given date.

##### Example output:
```
      Day 	Month   	Moon Phase 	 Time (UTC)	Year
0     2   	January 	Last Quarter    05:30     	2016
1     10       January 	 New Moon 	    01:30 	     2016
```


##### Authors

Ryan Ovsienko

##### License
This project is licensed under the MIT License - see the LICENSE.md file for details
