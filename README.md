# Assignment 2- Election for office as Governor of Pennsylvania (USA)

## Overview

### What is this website for?

This website is a coursework assignment for module 2 of the code institutes web development course.

### The goal?

The primary goal for this website is to display data from a CSV file in an interactive "data dashboard" format. This will consist of a number of chart types including bar, line and pie charts, each displaying selected information from the CSV file when selected. The theme for this assignment is to produce a website with the data dashboard feature, utilising data from the "school donations database" in order to present a candidate for Office as Governor of Pennsylvania (USA).

## Features 

### Existing Features
- Clean & clear Layout, fully responsive utilising bootstrap. Seamless "one page" design for ease of use and better presentation of topic material.
- Full navigation between sectons with responsive design. The site will load to the top of the "Our Candidate" section upon refresh.
- Home Section ("Our Candidate") introducing our candidate and general outline of major policys. Image of candidate and skyline view of Pennsylvania.
- Contact us section promiting candidate Rallies, as well as providing contact information for would be voters. Image of students attending a rally at the bottom of the section with the candidate's Slogan.
- Data Dashboard. Tutorial button for users with guidence for how to interact with this element of the site. Can navigate between tutorial points via "next"/ "previous" buttons. Powered by "introjs.css".
- Data Dashboard. Select district for PA box.
- Data Dashboard. Number of donations line chart.
- Data Dashboard. Poverty Levels Bar Chart.
- Data Dashboard. Resource types pie Chart.
- Data Dashboard. Funding Status pie Chart.
- Line breaks between sections.
- page footer.

### Features Left to Implement
-N/A

## Tech Used

### (SECTION TO BE COMPLETED)Some the tech used includes:

- [Bootstrap](http://getbootstrap.com/)
	- **Bootstrap** was used to give the website a clear and responsive layout with fully responsive navigation. Additional features from Bootstrap where also utilised such as glyphicons, buttons etc. 

- [Jquery](http://code.jquery.com)
  - **Jquery** used to add fuctionality to the discography page carosel, allowing track listings to change when the correct album art is navigated to.

- [bower](https://bower.io/)
	- **Bower** is used to manage the installation of our libraries and frameworks.

- d3.js
    - **D3** allows charts to render.

- dc.js/css
    - **DC** Used as a wrapper for D3 plugin. Simplifies chart parameters required in code. The .Css file contains parameters for chart stylings.

- CrossFilter
    - **Crossfilter** for exploring large datasets in browser and allows for data analysis.

- Queue.js
    - **Queue** is an asynchronous helper libary for data use, involving a number of api's. This plugin waits till data is available from each api before passing on the combined data for processing by the app.

- keen-dashboards
	- **Keen-dashboards** a template libary for the data dashboard.

- introjs.css/ .js
    - **Introjs** provides functionality for a tutorial to the data dashboard. When the "tutorial button" is pressed, a number of pop up windows will appear in sequence. Browsers will autofocus on these as the user selects next/ previous, till cancelled or all tutorial popups have been displayed.

- Pymongo
	- **Pymongo** is a plugin for python to allow it to access and interact with MongoDB.

- [Mongodb](https://www.mongodb.com/download-center)
	- **MongoDB** Allows for the deployment of a dataset into a database.

- [Heroku](https://signup.heroku.com/)
	- **Heroku** is the online platform used to host the Flask app (site).