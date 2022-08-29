Here it is, the mapty application.

- The main part of this application is a huge map which is loaded from a third party service.

  And also the position is actually automatically obtained by the browser using geolocation API and the map is loaded In our current position.

  I have linked this library to the project because I wasn’t familiar with NPM yet.

  The goal of this application is to log our workouts.
  As we click on the map, a minimal form will appear in the sidebar and we can specify type of our workouts, such as running and cycling.

- I have used OOP to implement this project.

  The task of this application are:

- get our position using geolocation
- load the map at our current position
- render our workouts
- render marker with nice popup
- ability to create new workout
- show and hide form
- as we click on our workouts that are in sidebar, it will automatically move the map to that workout.
- save the data in localstorage
