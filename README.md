This sample application is developed using node and express frameworks.
It provides following endpoints :-

### To get all movies from movies database
* GET    - /api/movies
### To get a single movie with specific id
* GET    - /api/movies/:id
### To create new movies
* POST   - /api/movies
### To update movies with specific id
* PUT    - /api/movies/:id
### To delete movie with specific id
* DELETE - /api/movies/:id   

## To run this application

1. Clone this project and then change directory to that folder and run `npm install`.

2. Run this application on port 5000 using the following command `export PORT 5000`.

3. Once the above command is successfull, run `node server.js` and it should bring up the application.
   You can test the application using the above end-points. The GET end-points can be accessed via browser.
   Other end-points (POST, PUT and DELETE), can be tested via PostMan tool or any other application, which is consuming these end-points.

There is a front-application which consumes these API's and can be found here.

### Endpoint to get all movies

![Get All Movies](https://github.com/mukesh51/c1-node-api-server/blob/master/images/GET-all-movies.png)

### Endpoint to get a single movie

![Single Movie](https://github.com/mukesh51/c1-node-api-server/blob/master/images/GET-single-movie.png)
