# Build Instructions

1. From your Android phone open a browser and navigate to http://jscpeterson.com/app-debug.apk

2. You will be prompted to download the file. Select DOWNLOAD.

3. After download is complete OPEN the download.

4. Your mobile device will likely prompt a security warning since the app is not being downloaded from the App Store. If this is the case, click on the SETTINGS button.

5. Toggle the switch to allow install from this source to the on position. Then hit the back button or okay button.

6. You will then see the title of the app, "Film Tour" with the icon in the top toolbar. This screen will ask if you want to install this application. It does not require any special access. Select INSTALL.

7. The app will install and you will see a message if it was successfully downloaded. If the download was unsuccessful start again from step 1.

8. Select OPEN to open the app for the first time.

9. For further help and instructions here is a link to our [User Instructions](https://abqfilmtour.github.io/docs/UsageInstructions.html). If you are experiencing difficulty with the download please [contact us](mailto:abqfilmtour@gmail.com).


## Advanced Build instructions for developers

### First clone/download the repository

From github click the "clone or download button" and copy the URL.

### Option 1: Import the project into Intellij IDEA

under the VCS dropdown menu select "checkout from version control" and select "git". Paste the copied URL into the URL box.
Select a directory to save the project and hit the "clone" button.

Then from the IntelliJ IDEA main menu select "Import Project".
 
Select ABQFilmTour from the directory it was saved in. Make sure that Gradle is selected or the project will not build properly.
Click the next button. On the next menu screen check the box "Use auto-import" and then click the finish button.

#### Synchronize the Gradle build

Intellij IDEA should do this automatically. If not in build.gradle(Module:app) file there should be an option to do so.

#### Execute the build

Under the Build drop down menu select "build".  

The app should now be ready to run. Selected the device you want to install it on and hit the okay button.


### Option 2: Import the project into Android Studio

From the welcome page select "checkout from version control" and select "git". Paste the copied URL into the URL box. Select a directory to save the project and hit the "clone" button.

You will be asked "Would you like to create an Android Studio project for the sources you have checked out to {project directory}". Select "Yes".

From the Import Project screen. Select Create project from external model and make sure that Gradle is selected. Then hit the Next button.

Check the use auto-import checkbox and select finish.

#### Synchronize the Gradle build

Android Studio should do this automatically. If not in build.gradle(Module:app) file there should be an option to do so.

#### Execute the build

Under the Build drop down menu select "build".  

The app should now be ready to run. Selected the device you want to install it on and hit the okay button.
