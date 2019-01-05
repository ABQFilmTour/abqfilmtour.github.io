# Usage Instructions

On first run, the app will ask for Google Sign-In authentication as well as permission to use the device’s location. Some features of ABQFilmTour will require this permission to run properly.

## Maps screen
On first run, the app will load data from the database and the progress will be shown with a simple spinner animation in the center of the screen. Once data has been loaded, the app will prompt the user to select a title to get started. If the user has already used the app, the map will automatically populate map pins of the last title the user selected. The user can select movie or TV show titles from the dropdown menu in the upper right corner of the screen to further narrow down the sites that they are interested in. Once a title is selected, corresponding location pins will be populated on the map. The user can manipulate the map as they would a typical Google Maps service. [Help with Google maps](https://support.google.com/maps/answer/144349?hl=en) When a user clicks on a map pin, a brief description snippet will pop up with the production title and site name. When the snippet is selected the user will be taken to the location screen.

## Drop Down Menu
The drop down menu is located on the top right hand side of the title toolbar.

### All Locations
Selecting the all locations option will populate the map with every location in the database. There are nearly 1,000 locations on the map so this is only recommended if the map is already zoomed into an area that the user is interested in.

### Near Me
A near me function is also available from the dropdown menu. If the user is within Albuquerque city limits, the map will zoom into the user’s location and populate map pins for all filming locations within approximately a mile radius. 

*Note* - the device's location must be turned on for this function to be useable.

### Film menu
Allows the user to select a film title that they are interested in. All corresponding filming locations will be populated on the map.

### Television
Allows the user to select a television show title that they are interested in. All corresponding filming locations will be populated on the map.

### Bookmarks
If the user has bookmarked locations, selecting this option will populate the map with all bookmarked locations. If the user does not have any bookmarked locations, the user will be prompted to select the bookmark button on an existing location.

### Submit
The submit option allows the user to submit their current location as a new film location. The app will automatically choose the last selected film or television series for submission. To change to a different title, select the film or television option from the drop down menu, select the new title and then select the submit option again. If the user has not yet selected a film or television series, they will be prompted to do so. Once the submission has been approved, it will display as a location on the maps screen.

*Note* - As this phase of development all locations are immediately approved, but traffic is still monitored.

If a production filmed in Albuquerque does not exist in our dataset, please [contact us](mailto:abqfilmtour@gmail.com).

### Sign Out
Allows the user to sign out of their Google account. If the user has not used the application for an extended period of time, the user may be prompted to sign out and sign back in again. It is recomended that the user signs out when they are no longer using the application.

## Location screen
When a user clicks on a map pin snippet, they will be taken to the location screen. The location screen displays the title of the production, and title of the filming location, a movie poster, a link to IMDB as well as a brief description of the plot summary. The user also has the ability to bookmark a location and review and leave comments. In future releases, user image uploads will also be available.

### Add a Bookmark
To the right of the production title is a bookmark button. Once selected it will highlight in yellow and the user will be notified that a bookmark was added. To remove a bookmark click the bookmark button again. The bookmark will no longer be highlighted and the user will be notified that a bookmark was removed. To view all bookmarked locations, select the bookmarks option from the drop down menu. Bookmarked locations are saved and can be accessed again on subsequent logins.

### Post a Comment
Towards the bottom of the screen is an orange button labeled "Post a Comment". When selected a text box will pop up. The user can enter a comment and hit the submit button to submit it. Once the submission has been approved, it will display as a comment below the post a comment button.

*Note* - As this phase of development all comments are immediately approved and are visible after refreshing location screen but traffic is still monitored.

### Post an Image
This feature is currently unimplemented. We plan to implement user submitted images in a later release.
