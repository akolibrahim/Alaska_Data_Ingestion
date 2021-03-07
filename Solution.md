# Alaska_Data_Ingestion

# Steps to examine the solution:

1) Flight_Search_Schema, Flight_Search_Results_Schema, Flight_Status_Schema, Checkin_Schema, and Manage_Trip_Schema JSON files contain the tags and possible events to model.
2) Tools_Processes.txt file describes various 3rd party tools to capture the events described in the above step. Moreover, pros/cons of each tool is described in here.
3) Data_Storage_Strategy.txt file explains the data flow to a storage strategy. It also has a walkthrough for the structure of the data.
4) Questions.md file contains some questions that came up while developing my solution.
5) We could answer the questions presented in the objective by:
    i) The ideal way to calculate the conversion rate would be getting the number of visitors who has completed a transaction out of the total number of visitors. We can count         the number of "clicks" from the search results page, however, to get the "actual" number of the conversion rate we still need to see the completed transactions.
    ii) We could see how the cost in miles affect the guests willingness to purchase by capturing the "use miles" click data from our search page. From there we could see how           many of our guests who has chosen to use miles actually ended up completing a transaction.
    iii) For the destinations that Alaska does not serve for the given airport or date we could collect the "From"/"To" and "Departure Date"/"Return Date" data from our Flight           Search page.
6) Even more questions could be answered from the data we collect from the Search and Search Results pages. For instance;
    i) Demanded flight routes. What flight destinations have the most demand from guests?
    ii) Are customers willing to pay more when there is less time before departure time?
    ii) In which markets and on what days people are likely to book/pay more?

# Notes:

1) 3rd party tools question should be answered with the company budget and long term goals in mind. The solutions I have provided assumes budget is not an issue.
2) Data capture and storage solution focuses on MS Azure Cloud storage because Alaska already has this technology.

# Benefits:
By extracting data from alaskaair.com we can do:
  1) Price Optimization by analyzing the pricing/purchase patterns and put competitive price tag for each flight.
  2) Analyze/Predict customer shopping trends.
  3) Learn about the customer choices and purchase patterns.
  4) New flight destination launch research.
  5) Understanding your travel booking funnel and what users are searching for.
