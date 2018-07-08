# Restaurant Review App

Contents:

- [Live Version](#live-version)
- [Project Description](#project-description)
- [Added Features](#added-features)
- [Local Usage](#local-usage)


## Live Version
https://koszojudit.github.io/JK-Restaurant-1-Udacity-FEND/


## Project Description
This is 6th project during the Udacity Front-End Web Developer Nanodegree Program.
Students were given a [starter code from Udacity](https://github.com/udacity/mws-restaurant-stage-1) to convert a static webpage to a mobile-ready web application.


## Basic functionality

Main page:
  - Map - showing the restaurants addresses
  - 2 dropdown filters - to filter the restaurants according to: "Neighborhood", and "Cuisine".
  - Restaurant cards - showing photo, name, neighborhood, address, view details button

Individual restaurant page:
  - previous mentioned details
  - individual restaurant map
  - opening hours
  - reviews for the restaurant


##  Added Features

### Responsive Design:
  - making UI Ucompatible with a range of display sizes (adaptive to screen widths from 320 px up to 1280px+)
  - responsive images (sizing appropriate to the viewport)

### Accessiblity:
  - accessible images with alternate text
  - focus management allows easy navigation of the site
  - semnatically defined elements and ARIA roles

### Offline Availability:
  Service worker enables the app to be available offline after the first use.


## Local usage

  1. After download, use a simple HTTP server to serve up the site files on your local computer.
  - If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
  - Navigate to project folder in your terminal.
  - Check the version of Python you have: `python -V`.
  - If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.)
  - For Python 3.x, you can use `python3 -m http.server 8000`

  2. With your server running, visit the site: `http://localhost:8000`.
