# To Do List ✅

This was the first full stack web app I built from scratch and deployed. I had a lot of fun putting some of the skills I had learned so far together! 

One of my main focuses for this project was better understanding communication between the server and client. I started by building a basic backend, including some HTTP request methods using Express Router. Then I set up my front end API requests and a React component to display the tasks. I kept the UI fairly clean and minimal. Task names are always lowercase purely as an aesthetic choice. Adding information from the multi-input form to the database was the most complex part of the project. Once my Task Form was complete, I added task sorting, delete, mark as complete and mark as incomplete functionality. I deployed this project using Dokku.

*See ToDoList in action [here](https://cae-todos2.devacademy.nz/).*

### Features:
- view tasks ordered by priority level
- add tasks (including priority level and description)
- mark tasks as complete
- delete tasks
- view completed tasks
- return completed tasks to the to do list

### Languages, Tools & Technologies:
- HTML
- CSS
- Typescript
- React
- Node.js
- Express.js
- SQLite
- Dokku

### Accessibility:
This webapp is compatitble with screen readers and keyboard only navigation. I checked the To Do List, Completed List and Form views using the WAVE accessibility extension. Keyboard only navigation was manually tested for all views. As some of the buttons have icons only, I manually tested the aria button labelling using Narrator screen-reader for all views. 
