# Google Names Batch Search

By: Shirsho Dasgupta (2021) 

The Miami Herald often works on investigations based on corporate records — sometimes public, at other times leaked. These records often have — or reporters can make it themselves — lists of companies, their owners and/or directors and other officers. 

This project was initiated to automate an initial search on who these people are. 

The code imports a spreadsheet with a list of names then searches for them in Google. It then extracts the first few lines about that person that come up as flashcard in a regular Google search.  

An short example is attached. 

The file that is imported is names.csv

The resulting file is search_results.csv

##### Notes:

1. This search is only to be used as a starting point. The results are not fully confirmed. Some of the ways in which one can obtain a complete confirmation is to match DOBs or photos. 

2. Overloading Google with queries can make their networks label the code as a bot and block access. Care must be taken to break the searches up and have sleep times between each iteration.

