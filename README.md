# Parktakes-Scrapy

Sample command-line usage: 

Shortform :python  ./ScrapeParktakes.py -p /tmp -c "AQUA++”
Longform  :python  ./ScrapeParktakes.py --path /tmp --category "AQUA++"


Result of each of the above commands is in CSV file created under the path specified.

Program Argument (Type)->

-p or --path  (Required)
-c or --category (Required)
-k or --keyword (Optional)
-s or --subject (Optional)
-a or --age (Optional)
-d or --day (Optional)
-w or --week (Optional)


Example - 

python ./ScrapeParktakes.py -p /tmp -c "AQUA++" 