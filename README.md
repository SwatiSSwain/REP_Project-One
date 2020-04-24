# REP_Project-One

METHODS:
Data Exploration
-Data from ProPublica API
-API calls were performed on each session of congress by chamber (to reduce burden on the server and timeouts)
-Saved relevant record fields into multiple csv files (from dataframes)

Data Cleanup 
-Looped through the folder to read all csv files and output it to a dataframe.
-The master dataframe was used to analyze data quality for the clean up process.
-Removed congress 112 data due to data inconsistencies
-Saved the clean data into one single csv file for trend analysis

Data Scope
-Congress 113th - 116th, 2013 - 2020
-Only bills(house and senate), not resolutions
-Data fields Included: bill number, sponsor information (chamber, state, party), subject, committees , dates for bill introduction, enactment

CONCLUSIONS:
Trends in Congressional Activities
-The House of Representatives introduces more bills and has more bills enacted than the Senate
-Bills tend to be introduced early on in the session. 
-Half of all legislation that will be enacted is enacted only in the final quarter of the session.

Trends in Enacted Bills
-Committee with most bills enacted: Home Security & Govt Affairs
-Primary Subjects on enacted bills: Govt Operations & Politics, Armed Forces and National Security, Health and Natural Resources
-Decision making of a bill: Significantly impacted by having different Sponsor party, House and Senate majority.
-Cosponsors on a bill: Having significant number of cosponsors(>300) entails that the bill has more support from senators and/or representatives and has more likelihood of success.
-Sponsor States with more representatives has more bills enacted
