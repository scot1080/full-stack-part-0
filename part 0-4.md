browser -> server: HTTP POST https://fullstack-exampleapp.herokuapp.com/new_note
note over server:
Adds a note to the notes database
end note
browser -> server: HTTP GET https://fullstack-exampleapp.herokuapp.com/notes
server -> browser: HTML document
browser -> server: HTTP GET https://fullstack-exampleapp.herokuapp.com/main.js
server -> browser: Javascript document
browser -> server: HTTP GET https://fullstack-exampleapp.herokuapp.com/main.css
server -> browser: CSS document
browser -> server: HTTP GET https://fullstack-exampleapp.herokuapp.com/data.json
server -> browser: JSON data 
browser -> server: HTTP GET https://fullstack-exampleapp.herokuapp.com/favicon.ico
server -> browser: Favicon image


