# Feed Reader Testing
My challange was to write tests for a web-based application that reads RSS feeds. I checked functionality of RSS Feed testing, RSS Feed properties, menu default state, and menu hiding/showing.

I used included [Jasmine](http://jasmine.github.io/) framework for testing JavaScript code.

## ./jasmine/spec/feedreader.js
- URLs and Names properties are defined and not empty
- Menu is hidden by default
- Menu changes visibility (display/hidden when clicked); simulate click event
- LoadFeed function loads a least one feed
- LoadFeed function changes the feeds content

[Demo](https://helenajagodnikkuhar.github.io/nanodegree-website_optimization/)

### Getting started
Clone the GitHub repository and run the index.html file in your browser. Or you can use the [Demo](https://helenajagodnikkuhar.github.io/nanodegree-website_optimization/)

### Tech

Web-based application that reads RSS feeds uses open source projects to work properly:

* [Jasmine](http://jasmine.github.io/) framework for testing JavaScript
* [Jquery] - JavaScript library 
* [Udacity API] - to load RSS feeds

### Contributing
Project assets were written as part of Frontend nanodegree Feed Reader Testing project submission. The material is [here](https://github.com/udacity/frontend-nanodegree-feedreader).
I wrote tests to test performance and functionality for RSS Feed testing, RSS Feed properties, menu default state, and menu hiding/showing by applying the techniques I've picked up in the [ JavaScript Testing course](https://www.udacity.com/course/javascript-testing--ud549).

### License
The contents of this repository are covered under the [CC BY 3.0 USß](https://creativecommons.org/licenses/by/3.0/us/).