# Cinema Information App
![Preview](images/preview.png "Preview")

## Project Description
Project 2 for *Dynamic Web Applications with JavaScript* course (Laurea UAS 5 ects). The aim was to develop a small-scale AJAX application using live REST API from Finnkino.

#### Requirements
- Application makes AJAX calls to a live REST API
- JavaScript and CSS kept in external files
- Only "native" JavaScript, no external libraries (JQuery etc.)
- Code is formatted and commented

## Features  
 :mag_right: User can choose an area or a specific cinema from a pull-down menu that lists the predefined options based on the user's data input   
 :abc: User can choose an area or a specific cinema by using custom search string field  
 :star: Search field recognizes some popular nicknames used for cinemas (such as *"Tennari"* for Helsinki Tennispalatsi or *"Omppu"* for Espoo Omena)  
 :exclamation: Empty or incorrect searches create an alert box  
 :white_flag: In case there are no shows on the current date, user is informed by an alert box  
 :ticket: After a cinema has been successfully chosen, a schedule will be displayed with the following data: an image of the movie poster / text *"Image not found"*, date, starting time, movie title, auditorium details, and duration  
 :heavy_plus_sign: Clicking the poster image or movie title opens a link to the movie's synopsis page on Finnkino in a new tab  
 :top: "Scroll to top" button becomes visible and usable when the user scrolls down 20px from the top of the document

## How to Run
This application is published in Netlify: https://chic-empanada-4d3c94.netlify.app/

## Technologies
- JavaScript
- HTML
- CSS
