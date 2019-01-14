# southwest-flight-count-scraper

Southwest Airlines Flight Count Data Scraper
Created by George Thompson

This data scraper will allow users to retrieve the count of available "one-stop" and "non-stop"
flights given origin and destination locations within a provided CSV file.

File: southwest-flight-count-scraper.py

------------------------CSV Formatting Guide-----------------------------------
[any field name]
OAK-ORD           # each line in this example represents a row in the CSV file.
OAK-ORD           # all entries can contain any 3 digit airport codes.             
OAK-ORD           # CAPS is recommended and the hypen ("-") is required!
-------------------------------------------------------------------------------

Since this program was created for one unique case, it's assumed that the user will not make errors
when prompted for data. Error handling was not implemented in this project for this reason.

Finally, some TODO's are scattered throughout the script for potential improvements I'll make if I
happen to revisit this project. Otherwise, this program achieves its purpose even though some code
could be written more elegantly.

WARNING: I did not run every flight in the "Test.CSV" so it's very possible Southwest's site
will eventually block your IP from running further searches. I'd prefer to learn Scrapy before
handling such issues in future webscraping endeavors.

WARNING: This was built in a Linux distribution, so the sheband line will need to be changed to run
this in OS X or Windows. Furthermore, my distribution's terminal would not copy the CSV file path
when dragging it onto it. If that the case, CD into the directory with the CSV and Python script,
then simply type the CSV file's name when prompted.
