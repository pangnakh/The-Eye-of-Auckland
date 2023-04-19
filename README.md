# The-Eye-of-Auckland

In a world with a steady rise of danger and crime in urban areas, people are becoming increasingly concerned about their safety and well-being. 

The Eye of Auckland is a solution proposed to provide users with all relevant insecure factors around them, so they have the knowledge to keep themselves safe. 

The Eye of Auckland will act as an app designed so users can access a visual heat map showing any incidents of concern within the radius surrounding them. With this information, all the residents of Auckland will know exactly where to keep safe and any dangerous places to avoid.

To achieve this application, the project will work in 5 parts:

## 1. Pre-process Decision Matrix: Design a matrix to locate relevant keywords to do with insecurity factors and filter out potentially fake data

## 2. Web Crawl: Using keywords from the decision matrix, connect to and query social media API's to extract data based on this information such as type of incident and geographical location

## 3. Data Cleaning and Processing: With the pulled data, clean the data to keep only keep the relevant data to do with the project, and export the data in a usable format. 

## 4. Store this data in AWS Cloud storage where it can be parsed into the application. The data will be continually cycled based on the intervals of querying for data from the APIs

## 5. Create a user friendly interface for visualisation for the insecure factors in the application. The visualisation will be in the form of a map which is connected to the Google maps API and then display a heatmap of the location of the insecure factors, and what type of incdent it is. 
