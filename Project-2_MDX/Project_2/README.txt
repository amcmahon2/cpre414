Team members: Andrew McMahon (individual)


Notes:

Query #3:
	-> For this one, I decided to omit the column which shows the Marital Status of each employee. Since they are all filtered out as married, I felt it was redundant to include that column of data.

Query #4:
	-> This query resulted in some of the products to have a null value for their average. When I went to check my database for these null entries, I found that they indeed had no value. Unsure if this was intended in the design of AdventureWorks DW (maybe to allow for testing of null values???), so I didn't add a wrapping NONEMPTY statement around my AVG function's logic. Due to this, some of the row entries in the resultant table appeared as null. Wanted to clear this up as I believe its an intended aspect of the AdventureWorks DW.

Query #5:
	-> This one caused a lot of trouble for me. I tried for nearly 3 hours to get the query to output something other than null, to no avail. The states appear fine, but I suspect that the ParallelPeriod() function isn't 100% compatible with our version of SSDT in Visual Studio. I am very certain my query is correct, so I just wanted to add a note in here that something may be wrong with the software version(s) we're using. It is also possible that I implemented the ParallelPeriod() function wrong, but I feel it is less likely, as I reviewed its documentation multiple times and found nothing wrong with my query.

KPI:
	-> I attached screenshots of right after I created the KPI. Hopefully that is sufficient enough for the assignment? I figured since it watches for trends, but no data is changing (i.e. there is no live data populating the database), it was unnecessary to attach a screenshot of its current state. But, if that is needed, I am mor than wiling to resubmit, or show my KPI working in person at the lab.