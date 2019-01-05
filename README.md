# ABQ Film Tour

### Aims
ABQ Film Tour is an Android app for tourists and film enthusiasts in the Albuquerque area. Users can find, submit, and discuss locations featured in locally filmed movies and television series such as "Breaking Bad" and "Better Call Saul". <br />
**Demo Reel Here** <br />
**Three screenshots here**

### Instructions
**Download Link Here**
[Build Instructions](docs/BuildInstructions.md) <br />
[Usage Instructions](docs/UsageInstructions.md)

### Test accounts
The minimum required Android API is 21. It has been successfully tested on Android emulators and devices running API 22, 23, 26, 27 and 28. There are no known compatibility issues. <br />
Location services are restricted to function only within Albuquerque city limits. <br />
The app runs in English with Spanish support. Data retrieved from IMDb resources are only offered in English. <br />
The app is configured to  only run in portrait orientation. <br />
**Accessibility**

### Team
Bio: We are alumni of the Deep Dive Coding Java+Android+Salesforce bootcamp through CNM. This application was originally our final team capstone project for the course. We are also submitting it for the UNM/CNM application contest and plan to continue development on it. <br />

Contact the team [here](mailto:abqfilmtour@gmail.com) or contact an individual member for more information:

[**Joseph Scott Peterson**](https://jscpeterson.github.io)
Fullstack developer, lead backend engineer, set up and maintained the server, set up API security, set up backend to frontend communication, activity stack management, shared preferences and layout design.

[**Samuel Andazola**](https://github.com/samz0la)
Frontend developer, design manager, created custom logo, splash page, map pins and app theme, in charge of UI/UX and layout design, created dynamic UX wireframes and mockups, worked on controllers and repositories in backend.

[**Rebecca Farish**](https://github.com/rebfarish)
Frontend developer, mathematics consultant, responsible for oauth2 authentication framework, device permissions, device location, user accessibility, and layout design, worked on controllers and repositories in backend.

### Documentation
[Frontend Java documentation](https://abqfilmtour.github.io/ABQFilmTour/docs/api/index.html) <br />
[Backend Java documentation](https://abqfilmtour.github.io/ABQFilmTourBackend/docs/api/index.html) <br />
[REST API documentation](https://abqfilmtour.github.io/ABQFilmTourBackend/docs/rest/api.html) <br />

### Functional inventory

- [Repository](https://github.com/ABQFilmTour/ABQFilmTour) for the client Android application that the end user will use.
- [Repository](https://github.com/ABQFilmTour/ABQFilmTourBackend) for the server side backend REST API. It is a Spring Boot project using an Apache Derby database.
- [Repository](https://abqfilmtour.github.io/OdeonClient/) for an in development client to assist privileged users in moderating the backend database.

### Prototypes
[Adobe XD Prototype](https://xd.adobe.com/view/81f12600-75b1-4f07-7cc3-a86bc45dacf9-f7c0/) <br />
[User Stories](docs/UserStories.md) <br />
[ERD](docs/ERD.pdf)

### Web service
[DDL](https://abqfilmtour.github.io/ABQFilmTourBackend/create.sql) <br />
The backend REST API for this application is hosted at jscpeterson.com. Endpoints are: <br />
jscpeterson.com/rest/users/ <br />
jscpeterson.com/rest/production/ <br />
jscpeterson.com/rest/film_locations/ <br />
jscpeterson.com/rest/film_locations/{location_id}/user_comments/ <br />
jscpeterson.com/rest/film_locations/{location_id}/images/ <br />
Endpoints are restricted to Android application users through Oauth2 authentication. Users with elevated privileges can view and modify the database with assistance from the OdeonClient project.

### State of completion
The application currently loads and can populate a map of Albuquerque with film locations stored in a backend database with certain filters provided by the user. The user can view all locations in the database, view all locations in their general vicinity, view locations associated with a film or television series, or view locations that have been flagged as bookmarked by the user. Opening a location map marker provides the user with more information about the production and shoot. The user can submit their location to an existing production in the database, or submit a comment to an existing location. When this project is officially released, these will not be displayed until approved by a member of the team. To fully demonstrate the capabilites of the application at this stage in development all submissions are approved immediately, however, a member of the team will be monitoring traffic and has the capability to ban malicious users from the service. 

### Stretch goals
- Complete image submission and retrieval for individual locations and. This feature is about 60% to completion.
- Creating a more elaborate user comment system with features including: better user comment boxes with timestamps and display images, a reply to comment feature, and an upvote/downvote voting system to encourage helpful commenting.
- Caching data on the local device so the app is still usable offline, using a persistence library such as ROOM.
- Improving the OdeonClient project to allow anyone who wants to assist with the team limited access to database features for moderation purposes. 
- Further backend security measures, such as request and submission throttling.

### Third-party libraries
- Google Maps
- Google Authentication
- Retrofit
- Apache CSV
- Circle Image View
- [Glide](http://bumptech.github.io/glide/)

### External services
-  Google Sign In
-  Google Maps
-  [OMDb API](http://www.omdbapi.com/)
-  [City of Albuquerque public film locations](http://data.cabq.gov/business/filmlocations/filmlocationsJSON_ALL) Retrieved on 12/3/2018

[Licenses](docs/Licenses.md) <br />

<sub>This site provides applications using data that has been modified for use from its original source, www.cabq.gov, the official website of the City of Albuquerque. The City of Albuquerque makes no claims as to the content, accuracy, timeliness, or completeness of any of the data provided at this site. The data provided at this site is subject to change at any time. It is understood that the data provided at this site is being used at one’s own risk.</sub>
