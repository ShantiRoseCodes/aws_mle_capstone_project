

### portfolio.json
* Create a new column called offer which assigns numbers 1 - 10 for each type of offer. This will be used as offer_id in the final table for readability.
* Extract each channel from the list of channels
* Create a new column for each channel 
* Input 0 if the offer was not sent using the channel, 1 if it is. 
* Drop channel columns
* Create a column with duration by hour.
* Reorganize all columns.
* Save dataframe to csv

### profile.json
* Remove NA values.
* Remove ages that are equal to 118.
* Find the membership duration in days using the difference between the maximum 'became member on' date and the actual 'became member on' date
* Rearrange the columns.