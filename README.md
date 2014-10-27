Taplist
=======

v0.3a

Simple beer tap listing using a json data source.  Responsive listing page displays what's on tap, and an admin page to manage the json data.


index.html
----------
The front-end.  Displays the data from the taplist.json.  Currently optimised for three taps, but the plan is for it to adapt correctly based on the data provided.


json_admin.html
---------------
The back-end.  A form to manage the json data.  Currently optimised for three taps, but the plan is for it to adapt correctly based on the data provided.


Todo
====
* Improve responsiveness of admin
* Improve adeptation to better support different numbers of taps
* Improve error handling across the board
* Preview tap display in admin
* Source tap data from file
 * <del>BeerXML</del> - basic implementation done
 * Support loading multiple taps if multiple recipes are in beerxml data
 * others?
* Source tap data from URL
 * BeerXML
 * beersmithrecipes.com
 * brewtoad.com
 * brewersfriend.com
* Link to beer on other sites
 * Untappd
 * Ratebeer
 * BeerAdvocate