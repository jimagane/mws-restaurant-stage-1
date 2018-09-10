# Restaurant Reviews App

Creates a website that enables to search for restaurant reviews by neighborhood and cuisine type. Displays map of restaurant location, basic restaurant info, and reviews, while utilizing responsive design, screen reader accessibility, and offline caching.

## Getting Started

Restaurant Reviews project can be cloned from github repository: https://github.com/jimagane/mws-restaurant-stage-1

### Prerequisites

Use text editor to edit any HTML, CSS, JS files, or add more data to the app.

Launch page server using Python. If Python is not installed, it can be downloaded from their website.

Use a browser to view the app.

### Installing and Usage

Clone program files from repository to run or edit.

To preview app pages, start a simple HTTP Server:

1. This can be done using Python. In terminal, run 'python -V' to check version.

2. Make sure you are located in the 'mws-restaurant-stage-1' directory in terminal.

3. If Python version is 2.x, run 'python -m SimpleHTTPServer 8000'

4. If Python version is 3.x, run 'python3 -m http.server 8000'

5. Use browser to visit local site: http://localhost:8000

## Running Tests

Refresh browser page to test modified code.

You can use Chrome Developer Tools to easily test site responsiveness for multiple devices, as well as mimic offline network to test service writer cache functionality.

ChromeVox Extension can be used to test screen reader accessibility features.

## Contributing

This repository for restaurant reviews project is for Udacity Front-End Web Developer Nanodegree course. Therefore, will not be accepting pull requests at this time.

For details, check out [CONTRIBUTING.md](CONTRIBUTING.md).

## Dependencies

Css normalize across browsers dependent on:
http://normalize-css.googlecode.com/svn/trunk/normalize.css

Leaflet map css dependent on:
https://unpkg.com/leaflet@1.3.1/dist/leaflet.css

Leaflet map js dependent on:
https://unpkg.com/leaflet@1.3.1/dist/leaflet.js

Map data dependent on:
https://api.tiles.mapbox.com/v4/

## Acknowledgements

All starter code and data other than css/responsive.css and sw/index.js provided by Udacity for project.

Codeowners listed as @forbiddenvoid @hbkwong.

Maps are provided by Mapbox using Leaflet.js.
