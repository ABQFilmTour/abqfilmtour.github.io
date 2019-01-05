# ABQ Film Tour

### Aims
ABQ Film Tour is an Android app for tourists and film enthusiasts in the Albuquerque area. Users can find, submit, and discuss locations featured in locally filmed movies and television series such as "Breaking Bad" and "Better Call Saul".

### Functional inventory

[Repository](https://github.com/ABQFilmTour/ABQFilmTour) for the client Android application that the end user will use.

[Repository](https://github.com/ABQFilmTour/ABQFilmTourBackend) for the server side backend REST API. It is a Spring Boot project using an Apache Derby database.

[Repository](https://abqfilmtour.github.io/OdeonClient/) for an in development client to assist privileged users in moderating the backend database.

### Team
[**Joseph Scott Peterson**](https://jscpeterson.github.io)
Fullstack developer, lead backend engineer, set up and maintained the server, set up API security, set up backend to frontend communication, activity stack management, shared preferences and layout design.

[**Samuel Andazola**](https://github.com/samz0la)
Frontend developer, design manager, created custom logo, splash page, map pins and app theme, in charge of UI/UX and layout design, created dynamic UX wireframes and mockups, worked on controllers and repositories in backend.

[**Rebecca Farish**](https://github.com/rebfarish)
Frontend developer, mathematics consultant, responsible for oauth2 authentication framework, device permissions, device location, user accessibility, and layout design, worked on controllers and repositories in backend.

### Web service
The REST API is hosted at jscpeterson.com. Endpoints are: <br />
jscpeterson.com/rest/users/ <br />
jscpeterson.com/rest/film_locations/ <br />
jscpeterson.com/rest/film_locations/{location_id}/user_comments/ <br />
jscpeterson.com/rest/film_locations/{location_id}/images/ <br />

### State of completion
**To be completed**
- Image submission/retrieval

### Test platforms
The minimum required Android API is 21. It has been successfully tested on emulators and phones running API 26, 27 and 28. Currently the app only runs in English and portrait orientation.

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

### Aesthetic goals
- Making user comment box more user friendly, display more information

### Stretch goals
- Handle picking from multiple images on the UI
- Request throttling
- Using room to cache data so the app is still usable offline, 

### Relevant Links

[Wireframes](https://xd.adobe.com/view/81f12600-75b1-4f07-7cc3-a86bc45dacf9-f7c0/)

[User Stories](docs/UserStories.md)

[ERD](docs/ERD.pdf)

[DDL](https://abqfilmtour.github.io/ABQFilmTourBackend/create.sql)

[Javadocs for the frontend](https://abqfilmtour.github.io/ABQFilmTour/docs/api/index.html) <br />
[Javadocs for the backend](https://abqfilmtour.github.io/ABQFilmTourBackend/docs/api/index.html)

[REST documentation](https://abqfilmtour.github.io/ABQFilmTourBackend/docs/rest/api.html)

[Licenses](docs/Licenses.md)

[Build Instructions](docs/BuildInstructions.md)

[Usage Instructions](docs/UsageInstructions.md)

<sub>This site provides applications using data that has been modified for use from its original source, www.cabq.gov, the official website of the City of Albuquerque. The City of Albuquerque makes no claims as to the content, accuracy, timeliness, or completeness of any of the data provided at this site. The data provided at this site is subject to change at any time. It is understood that the data provided at this site is being used at one’s own risk.</sub>
