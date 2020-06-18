# 6/18/20

It looks like instead of actually loading in the data across separate pages, they're actually loading in all the data at once and then selectively obscuring it using HTML. A beautifulsoup parse of this html found 1400+ logs, even though the table is only allowed to display 1000 logs at a time.




# Update - 6/17/20

As the cases in the county have gone up, the county has decided to move the data to a separate page with a different table structure that limits the number of records displayed to a thousand at a time.