# crumbmapper
QAnon Crumb Mapper - V1

This tool was written for QAnon patriots looking to make maps out of QAnon's crumbs.

It is:
* A browser based app - you download the crumb-mapper.html file and open it in a modern browser
* Uses some modern browser features - namely Blob and javascript classes
* It runs entirely local and makes no outgoing requests

It can create a map of information, including:
* entities (people, orgs, locations, etc)
* questions (from Q's posts)
* events
* links
* images (needs base64 encoded data, use a tool like https://www.base64-image.de)

To start:
* Click on the Data Import/Export Options
* Click Open
* Choose the starter-map.json
* Click Okay
* Map should load and display

To use:
* Select a object by click on it
* Select multiple by holding shift and clicking
* Connect two objects by select them in order and then clicking Connect button (enter label text in prompt)
* Double click to open/edit an object
* Add a new object using the buttons at the top (note, fields are not validated in V1)
* Click the Save button at the top to save to localStorage (browser db)
* Use Export options to save out a JSON file or populate the textarea for copying out
* Ctrl-click on a link to be prompted to open the url (on some browsers this doesn't work)
* Right click on the canvas/map and select "Save image as..." to save a picture
* Board is 3000x3000 - plenty of room!

Notes:
* Don't forget to list the posts wherein Q mentions the entity/event/question
* Avoid using images as much as possible, and use small ones, because the base64 data is big and the JSON file will grow fast
* Open urls with caution, use sites like https://archive.fo
* Feel free to report bugs to me here or on https://gab.ai/Justinon
* God bless you, patriots
