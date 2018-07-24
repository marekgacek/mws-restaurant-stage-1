# FEND Restaurant Review App

The project 6 of the [FEND with Udacity](https://eu.udacity.com/course/front-end-web-developer-nanodegree--nd001).

The main goal is to use service worker to cache the content and the site should have high accessibility.

## Get Started

### For Users

This is a website where you can search for your favourite restaurant. You can filter your search by location or cuisine type.

Use the dropdown lists to filter your result. The map is updating when you change restaurant/

You can see the details of the restaurants by clicking in the "View details of..." link.



### For Developers

- Clone the repository
- Go to the cloned folder
- I recommend using Python with the following command:

**Python 3**

`python -m http.server 8000`


- Go to _localhost:8000_ to open the website.
- The main HTML page is _/index.html_
- The restaurant's details HTML page is _/restaurant.html_
- The CSS file is _/css/styles.css_
- The JS file for the main page is _/js/main.js_
- The JS file for the restaurant page is _/js/restaurant_info.js_
- The JS file to fetch the data from the server is _/js/dbhelper.js_
- The service worker is located in _/service-worker.js_ and registered in the _/js/main.js_ file.
- The images are located in _/img_


## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.
