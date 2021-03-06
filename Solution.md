# Alaska_Data_Ingestion

# Steps to examine the solution:

1) Flight_Search_Schema, Flight_Search_Results_Schema, Flight_Status_Schema, Checkin_Schema, and Manage_Trip_Schema JSON files contain the tags and possible events to model.
2) Tools_Processes.txt file describes various 3rd party tools to capture the events described in the above step. Moreover, pros/cons of each tool is described in here.
3) Data_Storage_Strategy.txt file explains the data flow to a storage strategy. It also has a walkthrough for the structure of the data.
4) Questions.md file contains some questions that came up while developing my solution.

# Notes:

1) 3rd party tools question should be answered with the company budget and long term goals in mind. The solutions I have provided assumes budget is not an issue.
2) Data capture and storage solution focuses on MS Azure Cloud storage because Alaska already has this technology.

# Benefits:
By extracting data from alaskaair.com we can do:
  1) Price Optimization by analyzing the pricing/purchase patterns and put competitive price tag for each flight.
  2) Analyze/Predict customer shopping trends.
  3) Learn about the customer choices and purchase patterns.
  4) New flight destination launch research.
