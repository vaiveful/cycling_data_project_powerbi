Cycling Data Project

This Power BI dashboard shows data from my cycle journey between October 2023 and August 2025 through 21 countries.
It allows you to explore performance metrics, altitude highlights, geographic mapping, and monthly trends from over 18,600 km of cycling.

Dashboard Features
- Journey Summary: total distance, countries visited, days spent cycling
- Performance Metrics: daily averages, longest rides, time in the saddle
- Altitude Highlights: elevation gain, highest points, time spent cycling above 3000 m ASL
- Geographic Map: ride locations visualized by country
- Monthly Trends: distance cycled per month and year

Data Sources & Processing
I extracted the data from the Strava data export, which contained all the activities completed since starting to use Strava.
I then filtered the data to only show the rides for the relevant time period. Python scripts were used to process the .fit files from my Garmin device used for navigation, and ChatGPT helped to iterate the code to extract geographic information for mapping purposes. 

Requirements
Power BI Desktop version required in order to open .pbix file.

Screenshot
A preview of the dashboard is included in the repository as dashboard.png:

