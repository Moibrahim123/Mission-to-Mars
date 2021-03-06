# Mission-to-Mars

## Background

Robin’s web app is looking good and functioning well, but she wanted to add more polish to it. She had been admiring images of Mars’ hemispheres and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemispheres images. This requires additional scraping code to pull the high-resolution images, updating Mongo to include the new data, and altering the design of her web app to accommodate these images.

## Objectives

Use BeautifulSoup and Splinter to automate a web browser and scrape high-resolution images.
Use a MongoDB database to store data from the web scrape.
Update the web application and Flask to display the data from the web scrape.
Use Bootstrap to style the web app.

## Instructions

Visit the Mars Hemispheres (Links to an external site.) web site to view the hemisphere images and use DevTools to find the proper elements to scrape.

To complete this task, follow these steps:

 - Obtain high-resolution images for each of Mars's hemispheres.
Note: You must click each hemisphere’s link to access the full-resolution image’s URL.
 -  Save both the image URL string (for the full-resolution image) and the hemisphere title (with the name).
 - Use a Python dictionary to store the data using the keys `img_url` and `title.`
 - Append the dictionary with the image URL string and the hemisphere title to a list. This list will contain one dictionary for each hemisphere.
