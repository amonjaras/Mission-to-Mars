# **Mission to Mars**
Web scraping (HTML, BeautifulSoup Splinter, MongoDB, Flask, Bootstrap

## **INDEX**

- [Overview](#overview)

- [Resources](#resources)

- [Results](#results)

- [Summary](#summary)



## **Overview**
Robin's web app is looking good and functioning well, but she wants to add more polish to it. She had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to adjust the current web app to include all four of the hemisphere images. We will use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, store the scraped data on a Mongo database, use a web application to display the data, and alter the design of the web app to accommodate these images.

[:top: Go To Top](#index)

## **Resources**

- **Web Page scraping**
    - https://redplanetscience.com/ NASA Mars News
    - https://spaceimages-mars.com JPL Space images
    - https://galaxyfacts-mars.com Mars Facts
    - https://marshemispheres.com/ Mars Hemispheres

- **Software Used**
    - Python
    - Jupyter Notebook
    - Pandas, BeautifulSoup, Splinter, ChromeDriverManager, Flask, PyMongo
    - MongoDB
    - HTML5
    - Bootstrap 3

[:top: Go To Top](#index)

## **Results**
### **Code files**

- [Flask app](https://github.com/amonjaras/Mission-to-Mars/blob/main/app.py)
- [HTML Code](https://github.com/amonjaras/Mission-to-Mars/blob/main/Templates/Index.html)
- [Scraping Code](https://github.com/amonjaras/Mission-to-Mars/blob/main/scraping.py)

### **Code Results**

During the project we were able to scrape the most recent news related to Mars. The data scraped was stored  and displayed in a non-relational Mongo database.

Additionally, we were able to connect the scraping script with a click of a button, so that each time a button was clicked, the scraping occurred and the database gets updated, and new data was displayed.

This button only works under the condition that these webpages don't change their HTML components used for scraping.

By using Bootstrap grid system, we were able to create a responsive web app that will display the information in any device format.

[:top: Go To Top](#index)


## **Summary**

After using Bootstrap we were able to give a better format to the information displayed

> *Fig 1: Web page full window*

![Web Full View](https://github.com/amonjaras/Mission-to-Mars/blob/main/Images/mars_fullview.png)

> *Fig 2: Web page device views*

![Device View 1](https://github.com/amonjaras/Mission-to-Mars/blob/main/Images/mars_deviceview1.png)

![Device View 2](https://github.com/amonjaras/Mission-to-Mars/blob/main/Images/mars_deviceview2.png)

![Device View 3](https://github.com/amonjaras/Mission-to-Mars/blob/main/Images/mars_deviceview3.png)


[:top: Go To Top](#index)

This work belongs to [^1].
Course [^2].
[^note]:
[^1]: Author: Audrey MONJARAS :mexico: :canada:
[^2]: Data Analytics: Unit 10 Web Scraping with HTML/CSS 🌎
