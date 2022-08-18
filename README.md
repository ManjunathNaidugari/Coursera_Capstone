# Capstone Project - The Battle of Neighborhoods
## Business Problem Section
### Background
Many people want to invest their money in the business to make profits. There are different types of business like Restaurants, Shopping Malls, and Departmental Stores etc. It is better to start their business in major cities in the country. In this project, I’d like to study the neighborhoods in Chennai,
Tamil Nadu, India

### Business Problem
While starting a business, we need to search for a neighborhood that is suitable to their preferences. In this project, we study neighborhoods and venues to know which locality is good to set up a business.

The major Target Audience would be small-scale business owners and stakeholders planning to start their business at a location in Chennai. This project would help them find the optimal location based on the category of their business such as,

• What is the best location to start a Restaurant in Chennai?

• Which area is best suitable for opening a Shopping Mall and a Departmental Store in Chennai?

### Data Requirements
Chennai has multiple neighborhoods. The chennaiiq.com website has a dataset which has the list of neighborhoods in Chennai along with their Latitude and Longitude. Foursquare API is used to obtain the venue details in each neighborhood.

1. https://chennaiiq.com/chennai/latitude_longitude_areas.asp

2. https://www.foursquare.com

The Foursquare API is used to access the venues in the neighborhoods. Since it returns fewer venues in the neighborhoods, we would be analyzing areas
for which a countable number of venues are obtained. Then they are clustered based on their venues using Data Science Techniques. Here the k-means clustering algorithm is used to achieve the task. The optimal number of clusters can be obtained using silhouette score metrics. Folium visualization library
can be used to visualize the clusters superimposed on the map of Chennai city. These clusters can be analyzed to help small scale business owners select
a suitable location for their need, such as Hotels, Shopping Malls, Restaurants, Departmental Stores and Coffee shops.

There is a total of 105 neighborhoods. But the Latitude and Longitude data obtained are in Degrees Minute Seconds format which needs to be converted to Decimal Degrees Format.. The following data are obtained from the Foursquare API,

• Venue

• Venue Latitude

• Venue Longitude

• Venue Category data

A total of 1009 venues data have been obtained from Foursquare.
