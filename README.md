# Geo-Scraping South Los Angeles Toolset

## What is this?

This toolset is a wrapper around the GoogleMaps, Yelp, Weedmaps, and LA City/County SODA API to help you scrape and aggregate spatial data for further analysis 

## How do I use this?

Follow instructions below to run our program
 
1. Download Python 3.7.4
2. pip install requirements.txt
3. Gather API Keys (Google, Yelp, SODA)
4. Open keys.yaml with a text editor and make changes to keywords for Google and Yelp scrapes
5. If running windows, double click scrape.bat. If running Mac or Linux, double click scrape.sh.
6. Look inside output folder for csv's containing scrape 

## Uses for a program like this

Although this toolset was primarily made for Chapman's Crean College Health and Space Lab, it can be used for any location that each site hosts data for. For example: If you wanted to scrape location data of parks in Chicago, you would change the google latitude and longitude to the center point within Chicago and adjust the scrape radius.  

Problem: “Public Health and Public Admin Analysts are often frustrated by the effort it takes to manually record property types and locations.”
Solution: “Our scrapers eliminate that problem.”
Value: “With our repo, you can spend less time collecting data and more time conducting analyzing."
