# Plotly.ly-ChallengeBelly Button Biodiversity  - Interactive Dashboard built with HTML, Bootstrap, JavaScript, D3.js, and Plotly.ly.__GitHub Page :__ divya-gh.github.io/plotly.ly-challenge/## Table of contents* [Project Title ](#project-title)* [Description](#description)* [Objective](#objective)* [Screen Shots](#screen-shots)* [Technologies](#technologies)* [Code](#code)* [Status](#status)* [Acknowledgement ](#acknowledgement )* [Contact](#contact)## Project Title : Belly Button Biodiversity ### Description : This project aims at building a interactive dashboard to explore the Belly Button Biodiversity dataset, which catalogs the microbes that colonize human navels..### Data Set- The dataset reveals that a small handful of microbial species (also called operational taxonomic units, or OTUs, in the study) were present in more than 70% of people, while the rest were relatively rare.## Objective### Step 1 - BAR GRAPH:- Create a horizontal bar chart with a dropdown menu to display the top 10 OTUs found in that individual.- Using splinter navigate through [JPL Mars Space Images - Featured Image](https://spaceimages-mars.com/) and find the image url for the current Featured Mars Image.- Visit the [Mars Facts](https://galaxyfacts-mars.com/) webpage and use Pandas to scrape the table containing facts about the planet including Diameter, Mass, etc. and use Pandas to convert the data to a HTML table string.- Visit the [astrology](https://marshemispheres.com/) site to obtain high resolution images for each of Mar's hemispheres and create a dictionary.### Step 2 - MongoDB and Flask Application:- Use MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped from the URLs above.	- convert your Jupyter notebook into a Python script with a function called scrape that returns one Python dictionary containing all of the scraped data.	- create a route called /scrape that will import your scrape_mars.py script and call your scrape function.	- Store the return value in Mongo as a Python dictionary.	- Create a root route / that will query your Mongo database and pass the mars data into an HTML template to display the data.	- Create a template HTML file called index.html that will take the mars data dictionary and display all of the data in the appropriate HTML elements.## Screen Shots![Final App](./Missions_to_Mars/Images/final_app.png) ## Technologies and Tools* Jupyter Notebook* Visual Studio code editor#### Python Libraries* pandas* flask/jinja* Web Scraping libraries	* Splinter	* Requests	* BeautifulSoup4	* webdriver_manager		## Code - [mission_to_mars.ipynb](/Missions_to_Mars/mission_to_mars.ipynb)- [scrape_mars.py](/Missions_to_Mars/scrape_mars.py)- [Flask app.py](/Missions_to_Mars/app.py)## Setup1. Git clone this repository2. Open [Flask app.py](/Missions_to_Mars/app.py) in Visual code editor4. Execute the code to launch chrome browser containing scraped data from NASA's Mars sites.## StatusProject Complete## Acknowledgement - UTSA BootCamp## Contact [Divya Shetty](https://github.com/divya-gh) 