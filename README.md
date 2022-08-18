# Coursera_Capstone
{
 "cells": [
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "# Capstone Project - The Battle of Neighborhoods "
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "## Business Problem Section"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Background"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Many people want to invest their money in the business to make profits. There are different types of business like Restaurants,\n",
    "Shopping Malls, and Departmental Stores etc. It is better to start their business in major cities in the country. In this project, I’d like to study the neighborhoods in Chennai,  \n",
    "Tamil Nadu, India"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Business Problem"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "While starting a business, we need to search for a neighborhood that is suitable to their preferences. In this project, we study neighborhoods and venues to know which locality is good to set up a business."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "The major Target Audience would be small-scale business owners and stakeholders planning to start their business at a location in Chennai. This project would help them find the optimal location based on the category of their business such as,\n",
    "\n",
    "•\tWhat is the best location to start a Restaurant in Chennai?\n",
    "\n",
    "•\tWhich area is best suitable for opening a Shopping Mall and a Departmental Store in Chennai?\n"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "### Data Requirements"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "Chennai has multiple neighborhoods. The chennaiiq.com website has a dataset which has the list of neighborhoods in Chennai along with their Latitude and Longitude. Foursquare API is used to obtain the venue details in each neighborhood.  \n",
    "1.\t https://chennaiiq.com/chennai/latitude_longitude_areas.asp\n",
    "2.   https://www.foursquare.com"
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "The Foursquare API is used to access the venues in the neighborhoods. Since it returns fewer venues in the neighborhoods, we would be analyzing areas  \n",
    "for which a countable number of venues are obtained. Then they are clustered based on their venues using Data Science Techniques. Here the k-means clustering algorithm is used to achieve the task. The optimal number of clusters  can be obtained using silhouette score metrics. Folium visualization library  \n",
    "can be used to visualize the clusters superimposed on the map of Chennai city. These clusters can be analyzed to help small scale business owners select  \n",
    "a suitable location for their need, such as Hotels, Shopping Malls, Restaurants, Departmental Stores and Coffee shops."
   ]
  },
  {
   "cell_type": "markdown",
   "metadata": {},
   "source": [
    "There is a total of 105 neighborhoods. But the Latitude and Longitude data obtained are in Degrees Minute Seconds format which needs to be converted to Decimal Degrees Format.. The following data are obtained from the Foursquare API,\n",
    "\n",
    "•\tVenue    \n",
    "•\tVenue Latitude   \n",
    "•\tVenue Longitude  \n",
    "•\tVenue Category data   \n",
    "\n",
    "A total of 1009 venues data have been obtained from Foursquare.\n"
   ]
  }
 ],
 "metadata": {
  "kernelspec": {
   "display_name": "Python 3",
   "language": "python",
   "name": "python3"
  },
  "language_info": {
   "codemirror_mode": {
    "name": "ipython",
    "version": 3
   },
   "file_extension": ".py",
   "mimetype": "text/x-python",
   "name": "python",
   "nbconvert_exporter": "python",
   "pygments_lexer": "ipython3",
   "version": "3.8.5"
  }
 },
 "nbformat": 4,
 "nbformat_minor": 4
}
