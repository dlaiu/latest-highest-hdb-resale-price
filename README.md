# latest-hdb-resale-price
 This is a map of the latest most expensive resale price for HDBs per block in Singapore.

## Objective:
The goal of this project was to produce a "heatmap" of the resale prices of public housing in Singapore.

## What I did.
I pulled the data from data.gov.sg using the open API. I sorted the data by address and type of HDB flat.

To produce the data, I had to do some categorisation. I chose to use 4 different rankings depending on the max price of a resale flat at that particular address and the quartile prices of the entire dataset. I then had to pull the co-ordinate data from every address and combine it with the price dataframe. 

## Future plans
On hindsight this might not have been the most useful way to present the data. Bigger flats naturally would sell for higher than smaller ones. It might have been useful to split the dataset into the different price types and let people filter the points according to that. 

It might have also been useful to show price points by town to see where the "hot" areas are in Singapore. 

As an interactive feature, I would also want to implement a search function in the future. It might be interesting for readers to see how much flats in their block are going for. At the moment, it's not easy to find your exact address.
