# Note Taker Application

## Purpose of application
An application called Note Taker that can be used to write and save notes. It will help small business owners to be able to write and save notes so that they can organize their thoughts and keep track of tasks they need to complete.This application will use an Express.js back end and will save and retrieve note data from a JSON file. 

## Description
This is a note taking application. On landing page link to the notes page is avaialble. On click of link notes page will be displayed with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column.On entering a new note title and the note’s text a Save icon appears in the navigation at the top of the page. On click of save icon new note entered is saved and appears in the left-hand column with the other existing notes. On click of an existing note in the list in the left-hand column, that note appears in the right-hand column. On click of the Write icon in the navigation at the top of the page empty fields to enter a new note title and the note’s text will be displayed in the right-hand column. On click of delete icon for perticular note, that note will get deleted from the system.

## User Story
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete

## Acceptance Criteria
GIVEN a note-taking application
WHEN I open the Note Taker
THEN I am presented with a landing page with a link to a notes page
WHEN I click on the link to the notes page
THEN I am presented with a page with existing notes listed in the left-hand column, plus empty fields to enter a new note title and the note’s text in the right-hand column
WHEN I enter a new note title and the note’s text
THEN a Save icon appears in the navigation at the top of the page
WHEN I click on the Save icon
THEN the new note I have entered is saved and appears in the left-hand column with the other existing notes
WHEN I click on an existing note in the list in the left-hand column
THEN that note appears in the right-hand column
WHEN I click on the Write icon in the navigation at the top of the page
THEN I am presented with empty fields to enter a new note title and the note’s text in the right-hand column

## API routes
* GET /api/notes - read the db.json file and return all saved notes as JSON.
* POST /api/notes - receive a new note to save on the request body, add it to the db.json file, and then return the new note to the client.
* DELETE /api/notes/:id - receive a query parameter containing the id of a note to delete.

## HTML routes
* GET /notes - return the notes.html file.
* GET * - return the index.html file.

## Commands to Install dependencies 
* npm init - to add package.json file
* npm i express - to install express package
* npm i uuid - to install uuid package to generate unique id.

## Mock up images
The following image demonstrates the application functionality:

<div>
    <img src="./public/assets/images/notes.png" width="400px"/> 
</div>

## Built With
* HTML
* CSS
* JavaScript
* node js
* Express package
* uuid package (to generate random id for note)

## Heroku Website URL
https://shielded-atoll-29126.herokuapp.com/