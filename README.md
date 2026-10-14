# TimeEdit calendar reformatter

This is a simple python script that can either be used as a CGI script or simply to write an updated calendar into the same directory.

It will extract the fields from the titles of the events in the calendar, allowing you to remove/reorder fields as you like. 
It also has support for custom replacements, so that you can remove or shorten words in the event title.
The program will also reformat the location field of the event.

This all means that the event titles are much shorter, meaning more information is displayed on smaller displays without the need to open the full details of the event.

There are comments in the script which should make it easy to understand how to adapt it to your preferences.

**Please note that this script has only been tested on calendar feeds from my university, and your school/college/university will have different fields in the event title and location, meaning this script will almost certainly
require changes to work with your calendar feed**

### Example of what it can do:

`Module Code: AB1234. Module Name: Turnip Studies, Activity Type: Lecture (recorded), Staff: Mr Root Vegetable`

becomes

`AB1234: Lecture (rec.) w/ Mr Root Vegetable` (with the full module name in the description)
