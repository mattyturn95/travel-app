<h1 align="center">
  <a href="https://stiofaneimeid.github.io/travel-app/" target="_blank"><img src="https://github.com/stiofanEimeid/travel-app/blob/master/assets/images/routeRepLogofinal.png" alt="routeRep Logo"/></a>
</h1>

<div align="center"> 

[Go to the site!](https://stiofaneimeid.github.io/travel-app/)

</div>


# Stephen Byrne Portfolio

Stream Two Project: Interactive Frontend Development - Code Institute 

The routeRep travel application uses the Google Maps and Places APIs to allow users to select a location and find places to visit, stay and dine.
Users may then add these results to an itinerary. They may then continue to edit this itinerary to help plan their perfect trip. 

## Table of Contents
1. [**UX**](#ux)
    - [**Project Goals**](#project-goals)
    - [**User Goals**](#player-goals)
    - [**User Stories**](#user-stories)
    - [**Design Choices**](#design-choices)
    - [**Wireframes**](#wireframes)

2. [**Features**](#features)
    - [**Demo**](#demo)
    - [**Existing Features**](#existing-features)
    - [**Features Left to Implement**](#features-left-to-implement)

3. [**Technologies**](#technologies)

4. [**Testing**](#testing)

5. [**Deployment**](#deployment)
    - [**How to Run Code Locally**](#how-to-run-locally)

6. [**Credits**](#credits)
    - [**Media**](#media)
    - [**Acknowledgements**](#acknowledgements)

## UX

### Project Goals

...

### User Goals

...

### User Stories

I aimed to design a site that captured the idea of escapism while developing site functionality that allowed users to research and plan various aspects of a trip with ease. 

The user is greeted with a full-sized image of a forest, with the app’s brand name and logo taking up a small amount of space in the centre of the image. A mouse SVG provides an unobtrusive cue for the user to scroll down. The minimalist design is intended to give the user a sense of calm, ideally the same feeling a holiday provides. 

Directly below this image is an introductory section that provides some basic guidance about how to use the app. The app is designed to be as intuitive as possible and so the text here was kept to a minimum. 

The app itself asks users to choose a country and then enter the name of a city in that country. The map responds to each request, panning to the country and then to the city. The user then chooses from one of three options what they’d like to search for in the city, someplace to dine, someplace to visit, or someplace to stay. Markers are dropped into the map and the corresponding search results are displaced in a table alongside the map. Hovering over the markers causes a small text box to pop up providing some more information about the target. The corresponding search results are accompanied by a span containing a plus button that allows users to add places of interest to them to an itinerary at the bottom of the page. Once the user is finished, she will have a list of all the places of interest to her. 

The user will be greeted by a welcome image that includes the app name. 

Following this, an introductory section will set out some basic guidance about how to use the app. 

This section will be followed by another section containing the Google Maps API allowing users to select their destination. 

The final section, the itinerary, will be a bullet-point style list that consists of choices made by the user regarding their journey.

### Design Choices

The overall feel of this site is ... The following design choices were made with this in mind:

**Fonts**

- The primary font **x** was chosen because...
- The secondary font **Y** was chosen for...

**Icons**

- list items here

**Colours**

- list colours and reasons here

**Styling**

- list items here

**Backgrounds**

- list items here

### Wireframes

This [wireframe](https://github.com/stiofanEimeid/travel-app/blob/master/assets/wireframes/TA-wireframe.jpeg "wireframe") illustrates early conceptions of the site. This [second wireframe](https://github.com/stiofanEimeid/travel-app/blob/master/assets/wireframes/routeRepfinal.jpeg "second wireframe") gives an impression of the final look of the site.


## Features

### Demo

<div align="center"> 

![demo gif](https://github.com/stiofanEimeid/travel-app/blob/master/assets/images/ezgif.com-optimize.gif "demo gif")

</div>

### Existing Features

The app uses the Google Maps and Google Places API to provide search results about accommodation, places of interest and places to eat. Each individual result may be added to a list below the map so user's can keep track of the places they wish to visit, stay or dine.

### Features left to implement 

In the future, I would like users to have the ability to save their composed itineraries in the form of a PDF. At the moment, they receive an error message contained in a modal when they click the save button. 

## Technologies Used

- This project uses HTML, CSS and JavaScript programming languages.
- [JQuery](https://jquery.com)
    - The project uses **JQuery** to simplify DOM manipulation.
- [Cloud9](https://c9.io) 
    - Developer used **Cloud9** for their IDE while building the website.
- [Bootstrap](https://www.bootstrapcdn.com/)
    - The project uses **Bootstrap** to simplify the structure of the website and make the website responsive easily.
    - The project also uses Bootstrap to provide icons from [FontAwesome](https://www.bootstrapcdn.com/fontawesome/)
- [Unsplash](...)
- [Google Fonts](https://fonts.google.com/)
    - The project uses **Google fonts** to style the website fonts.
- [Google Maps](...)
- [Google Places](...)
- [Favicon](...)
- [EZgif](...)

## Testing

Information on the testing process may be found in the [testing.md file](https://github.com/stiofanEimeid/travel-app/blob/master/testing.md). 

## Deployment

The site was built using Cloud's IDE, added, commited and pushed to GitHub using the terminal. A live version of the site is hosted on GitHub pages. 

### How to Run Code Locally

In order to run a repository locally, the repository must be cloned. To clone the repository
:
1. Follow the link to the [routeRep GitHub repository](https://github.com/stiofanEimeid/travel-app).
2. Under the repository name, click "Clone or download".
3. In the Clone with HTTPs section, copy the clone URL for the repository. 
4. In your preferred IDE, open the terminal.
5. Change the current working directory to the location where you want the cloned directory to be made.
6. Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
7. Press Enter. Your local clone will be created.

Further reading and troubleshooting on how to clone a repository from GitHub may be found [here](https://help.github.com/en/articles/cloning-a-repository).

## Credits

### Media

The photo is by Lukasz Szmigiel and was found on Unsplash, a stock image library. It was later compressed using [compressjpeg.com](https://compressjpeg.com/ "compressjpeg.com").

### Acknowledgements

The SVG mouse found at the top of the site was initially found on page one, entry no. 3 of this [css animations page](https://www.creativebloq.com/inspiration/css-animation-examples "css animations page")
which displayed code this codepen: [SVG mouse](https://codepen.io/matchboxhero/pen/gGdJYo "SVG mouse").

The planning section’s map functionality was modelled after the code contained in the [Google Maps API documentation](https://developers.google.com/maps/documentation/javascript/examples/places-autocomplete-hotelsearch "Google Maps API documentation"), 
specifically an example about how to search for hotels by selecting a country and a city. It was modified to include searches for places of interest and places to dine. Changes were also made to allow users to push results to a list. 

The jQuery code that causes the three div elements in the information section to fade in on scroll was found here:
[FadeIn on Scroll(jQuery)](https://jsfiddle.net/tcloninger/e5qaD/ "FadeIn on Scroll(jQuery)").

The triangle divs used to create lens effects were generated using this [triangle generator site](http://apps.eky.hk/css-triangle-generator/ "triangle generator site") before changing the size, colour and opacity. 

The GIF demonstrating how to use the planner was shot with the capture screen feature of Quicktime and converted to GIF format using this site, [ezgif.com](https://ezgif.com/ "ezgif.com").

The site's favicon was generated using [favicon-generator.org](https://www.favicon-generator.org/ "favicon-generator.org").

Text gradient code was found at [css-tricks](https://css-tricks.com/snippets/css/gradient-text/ "css tricks").

Finally, this README.md was written with the help of this [guide](https://github.com/AJGreaves/familyhub/blob/master/README.md#code).
