# Mission-to-Mars

## Project Overview 
Performing data analytics and making a case for a shop (surf/ice creame/shake). It is important to check and make weather analysis of the island you would like to open the shop. 

1. Using Web Scraping Tools
2. Open the Window to the Internet
3. Automate a Web Browser and Perform Web Scrape
4. Access Data in MongoDB
5. Display Data with Flask
6. Making it visually pretty

This module has taught me the following:

1. Scrape Mars Data: The News, Featured Image, Mars Facts
2. Export to Python
3. Access Data in MongoDB and store the Data
4. Display the Data with Flask
5. Create a portfolio

## apps Folder
- template folder
        - index.html : The html framework to disply the data
- app.py: The code that shows the routing and mongodb
- chromdriver.exe
- scraping.py : The code that shows how to scrape the data from the sites

## template portfolio- 03
- assets folder
        - css - style
        -image - to insert images
- index - the content in the portfolio
        
## Documents

- .gitignore
- Mission_to_Mars.ipynb
- Practice.ipynb

## Summary

The scraping.py is the code that scrapes and find the data of the recent news, featured image, and mars facts. It accesses the data in Mongo DB and sotres the data, and displys with flask. The index.html is the framework on how the information is displayed. 

The data and information displayed in the flask and in the host will change depending on the most recent information is on the website that it's scraping from. 

The output of the data is the following:

  - Latest Mars News
  - Featured Mars Image
  - Mars Facts
  
## Portfolio

I started to edit my portfolio by adding information and resume details. I still need to go back and look over the projects I have completed to add to this. 

I also began changing the styling a little bit... the font and colors.
  
# Module 10 Challenge 

## Challenge overview

1. Obtain high-resolution images for each of Mar’s hemispheres.
2. Save both the image URL string (for the full-resolution image) and the hemisphere title (with the name).
3. Use a Python dictionary to store the data using the keys `img_url` and `title.`between June and December and 4. Append the dictionary with the image URL string and the hemisphere title to a list. This list will contain one dictionary for each hemisphere.

## Summary Challenge
***Please note the code/information can be found scraping.py and template.html

Completing the summary challenge, the hemisphere high quality images and image name is appended in a dictionary, looped, and displayed. In order to display the information, I created a loop in the html file and changed the size of the image to look nicer in the flask/output. 




