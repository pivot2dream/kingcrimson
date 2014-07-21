kingcrimson
===========

- Create a table with the following columns: band name, album title, number of discs, release date, recording date, personnel
- The album title should link to the provided wiki page
- Any missing data points should be represented with the string ‘—‘
- All columns except the personnel column should be sortable via links/buttons in the table header
- A filter form should appear above the table. This filter form should have fields to allow the filtering for all of the columns in the grid
- It should be possible to clear all the filters
- When a filter is applied an indicator that says “N of 39 albums matched your search”
- The order of the columns must be customizable by dragging and dropping the columns into a different order
- An additional form (possibly shown in a dialog window) allows the user to hide or show columns from the grid
 
 
Fulfilled Constraints
 
- The application has to work in the latest versions of Chrome, Firefox, Safari, and IE11

#### To Run

- Simply clone the repo and open index.html in a webbrowser

##### OR 

- visit http://www.aaronduchateau.com/music_cleaned/

#### JS Libraries Used 
- jQuery: good include for dom manipulation, animation, and other common tasks
- jQuery-ui: a default include for drag and drop
- dragtable.js: expands on jQuery UI for column sorting
- sortelements.js: tiny library that aids in a b sorting
- bootstrap: good for responsiveness, modals, buttons, etc. A default include
- helper.js: this is the primary chunk of code i wrote for core functionality
- qunit.js: a client side testing library. I had never used it before, and wanted to play with it
- tests.js: the tests I wrote, utilizing qunit
- backstretch.js: Not needed, similiar effect can be done with css. I just think it looks cool :)



