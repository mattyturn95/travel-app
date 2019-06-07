# routeRep - Testing details

[Main README.md file](README.md)

## Table of Contents

1. [**Automated Testing**](#automated-testing)
    - [**Validation services**](#validation-services)
2. [**Client Stories Testing**](#client-stories-testing)
3. [**Manual Testing**](#manual-testing)
    - [**Testing undertaken on desktop**](#testing-undertaken-on-desktop)
    - [**Testing undertaken on tablet and phone devices**](#testing-undertaken-on-tablet-and-phone-devices)
4. [**Bugs discovered**](#bugs-discovered)
    - [**Solved bugs**](#solved-bugs)
    - [**Unsolved bugs**](#unsolved-bugs)
5. [**Further Testing**](#further-testing)

## Automated Testing

### Validation services
The following validation services and linter were used to check the validity of the website code.
- [W3C Markup Validation]( https://validator.w3.org/) was used to validate HTML.
- [W3C CSS validation](https://jigsaw.w3.org/css-validator/) was used to validate CSS.
- [JSHint](https://jshint.com/) was used to validate JavaScript.


## Client stories testing

The user is prompted to choose one of thirteen countries contained in the dropdown menu and then a city in that country. Choosing all from the dropdown menu will allow the user to select any city in the world. 
Clicking on the span containing the plus symbol in the results table will add that result to the itinerary. Clicking on the cross contained in the span symbol will remove that item while clicking the name itself will toggle a strike-through css property on the relevant name.

If the user clicks the visit, stay or dine button without first selecting a country and/or city, Montluçon, France will act as the default city.

Alternating between different options to visit, stay and dine lays down relevant markers but also erases markers from the previous choice. Nevertheless, by adding lcoations to the itinerary users can keep track of their choices.
Changing city does not affect items contained in the itinerary although users may find it difficult to differentiate between choices relating to different cities. 

If the user wishes to choose a city located outside of the twelve featured in the dropdown menu, they may choose the "all" option from the same menu.

The user may add the same option multiple times. Duplicates, mistakes or choices no longer desired may be deleted by clicking on the close span appeneded to the end of each list item.

If the user clicks the save button, whether or not the list is populated a modal will be displayed. The modal gives the user an error message and that the site is unable to save the list.

Marker images from Maps/Places API blocked, visible incognito - cookie issue?

## Manual Testing

### Testing undertaken on desktop

### Testing undertaken on tablet and mobile devices

This site was tested across multiple browsers (Chrome, Safari, Internet Explorer, FireFox) in Google Dev tools(Galaxy S5, Pixel 2/Pixel 2 XL, iphone 5/SE/6/7/8 Plus, X, ipad and ipad Pro) and on multiple devices, mobile (iPhone 4, 5, 7: , OnePlus 6,Chrome and Safari) and otherwise(Macbook Air and Mac Desktop) to ensure compatibility and responsiveness.

## Bugs discovered

### Solved bugs

When testing the site on a OnePlus 6, I noticed that the second Triangle ended in the corner of the screen rather than the corner of the image. As a result, it appeared to be floating partway up the side of the image. Setting the bottom property to zero did not resolve the issue.
I fixed this issue by using a calc value for this triangle's top property in css. The triangle's height was 200px and the background image's height was 100vh, so I set ```top``` to ```calc(100vh - 200px)```, placing the triangle the correct distance from the bottom of the image. 

### Unsolved Bugs

The Google Places API documentation provided an example of code that allowed users to find a hotel in a selected city. After choosing a country from a dropdown menu, the map would pan to that country. When the user entered the name of a city into the search box the map would pan to that city and markers would drop on the map, indicating hotels in the chosen city.
I modified the code so that when the user selected a country or a city, markers would not immediately appear indicating hotels. Instead, I took the code that identified hotels and added it to an event listener. This function would only be triggered when the user clicked the button the event listener targeted, labelled 'stay'. I repeated this process for buttons labelled 'visit' and 'dine', that
displayed markers on places of interest and places to eat on the map when clicked. The API identifies places to put markers based on the 'types' property in the search object. The types lodging and restaurant were conventiently available already, but there was no equivalent for places of interest or tourist attractions. Instead, I included multiple types that fell under this umbrella, including 
"museum", "park", "zoo", "art_gallery", "church" to provide satisfactory results.

## Further Testing

...