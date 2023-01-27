# Mission-to-Mars
## Introduction
This project contains two main deliverables - scraping article titles and preview text from <a href="https://redplanetscience.com/" target="_blank"> Mars Temperature Data Site</a> and scraping and analyzing Mars weather data from <a href="https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html" target="_blank">Mars Temperature Data Site</a>.
### Deliverable 1: Scrape Titles and Preview Text from Mars News
In this deliverable, I initially scraped the date from the website using the provided URL. After that, data were organized using the Beautiful Soup python module in Jupyter. Titles and preview texts of all articls from the website were extracted and saved into a list of dictionaries, which were later saved and exported into a JSON file. Following that, I analyzed and then visualized the data.
### Deliverable 2: Scrape and Analyze Mars Weather Data
In this deliverable, I scraped an HTML table into a pdandas data frame in Jupyter. In doing so, the data was accessible for further analysis and visualisation. Some of the analyses were calculating the number of Martian months, and Martian days. I also looked into the average temperature in Mars, organized that per month, and then previewed that in a plot for the reader to have a better grasp of the data. Finally, the data frame was exported into a CSV for future use.
