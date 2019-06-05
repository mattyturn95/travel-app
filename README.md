# Stephen Byrne Portfolio

Stream Two Project: Interactive Frontend Development - Code Institute 

## Technologies
1. HTML
2. CSS
3. JavaScript
4. Bootstrap (4.3.1)
5. FontAwesome(v5.8.2)
6. GoogleFonts
7. Google Maps
8. Google Places


## Demo

![demo gif](https://github.com/stiofanEimeid/travel-app/blob/master/assets/images/ezgif.com-optimize.gif "demo gif")


## UX

I aimed to design a site that captured the idea of escapism while developing site functionality that allowed users to research and plan various aspects of a trip with ease. 

The user is greeted with a full-sized image of a forest, with the app’s brand name and logo taking up a small amount of space in the centre of the image. A mouse SVG provides an unobtrusive cue for the user to scroll down. The minimalist design is intended to give the user a sense of calm, ideally the same feeling a holiday provides. 

Directly below this image is an introductory section that provides some basic guidance about how to use the app. The app is designed to be as intuitive as possible and so the text here was kept to a minimum. 

The app itself asks users to choose a country and then enter the name of a city in that country. The map responds to each request, panning to the country and then to the city. The user then chooses from one of three options what they’d like to search for in the city, someplace to dine, someplace to visit, or someplace to stay. Markers are dropped into the map and the corresponding search results are displaced in a table alongside the map. Hovering over the markers causes a small text box to pop up providing some more information about the target. The corresponding search results are accompanied by a span containing a plus button that allows users to add places of interest to them to an itinerary at the bottom of the page. Once the user is finished, she will have a list of all the places of interest to her. 

The user will be greeted by a welcome image that includes the app name. 

Following this, an introductory section will set out some basic guidance about how to use the app. 

This section will be followed by another section containing the Google Maps API allowing users to select their destination. 

The final section, the itinerary, will be a bullet-point style list that consists of choices made by the user regarding their journey.

This [wireframe](https://github.com/stiofanEimeid/travel-app/blob/master/assets/wireframes/TA-wireframe.jpeg "wireframe") provides a rough idea of the look of the final product. 


## Features

The app uses the Google Maps and Google Places API to provide search results about accommodation, places of interest and places to eat. 

### Features left to implement 

...


## Testing

How was the outcome in the user story achieved?

Bugs…selecting a place to dine without choosing a city; revert to default.

Alternating between different options (stay, dine, visit). Changing city and erasing list. 

Adding the same option multiple times. 

Browser compatibility 

## Deployment

This site is hosted using GitHub pages, deployed directly from the master branch. The deployed site will update automatically upon new commits to the master branch. In order for the site to deploy correctly on GitHub pages, the landing page must be named index.html.

To run locally, you can clone this repository directly into the editor of your choice by pasting git clone https://github.com/...git into your terminal. To cut ties with this GitHub repository, type git remote rm origin into the terminal.
 
## Credits

### Media

The photo at the top of the app was taken from unsplash, a stock image library. 

### Acknowledgements

[SVG mouse](https://codepen.io/matchboxhero/pen/gGdJYo "SVG mouse")

The planning section’s map functionality was modelled after the code contained in the Google Maps API documentation, specifically an example about how to search for hotels by selecting a country and a city. It was modified to include searches for places of interest and places to dine. Changes were also made to allow users to push results to a list. 

[google maps documentation](https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch "google maps documentation")


