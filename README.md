# -Mission-to-Mars-
For this challenge I created a python script in my scraping.py file which defines functions to scrape various pieces of information from NASA's website. On the website I've created you can see latest news, mars facts, a featured image of mars, and titles and images of hemispheres all scraped from NASA's website and updated at the press of a button.

My app.py file imported my scraping.py file to use in a Flask application. In this app.py file, I created a Flask application, set up a mongo connection, built a root route and scrape route, and called the scape_all() function created in the scraping.py file. This calls all of the functions that scrape the data in my scraping.py file. 

I also edited a provided html template to customize the page a bit. Along with some formatting changes, I added in a for loop to reference the hemisphere function I created in scraping.py, which shows the images and titles of differente hemispheres. 

Once running the app.py file in terminal and following the provded local host link, there's an option to push the "Scrape New Data" button, which uses my code to scrape new data from NASA's website and return it to my own. 

![](/mars_website.JPG)
