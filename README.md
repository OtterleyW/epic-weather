# epic-weather
App for temperature observations

Heroku: http://epic-weather.herokuapp.com/

Backend: Node.js (Express), PostgreSQL

Frontend: React


In this app you can add temperature observations from five different locations: Tokyo, Helsinki, Amsterdam, New York and Dubai. You can also see latest observation of the location and highest and lowest temperature in past 24 hours. 

App is functional, but like all software projects, it could be improved.

Thoughts and known problems:
- It would be simple to implement adding of locations later, as the locations are stored in database.
- App currently has no tests. Tests would be nice.
- Temperature validation could need a little more work, especially if the app were to be used in research. Right now validations are quite simple.
- Adding a new observation will close all open observation accordions. This is because all components render again when state changes. 
- On mobile, adding negative temperature to new observation is tricky (but possible)
- Observations are called "perceptions" in code because, you know, naming things can get difficult 😅
