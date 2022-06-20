# Budget Tracker Progressive Web Applications (PWA) Project 19
https://budgettrackerbt.herokuapp.com/

## Mock-Up
The following image shows the web application's appearance and functionality:
<img width="80%" alt="Budget Tracker Img-1" src="https://user-images.githubusercontent.com/98120553/174515359-61082ca3-be4e-4cfa-a1d6-0262f2a230d3.png">
<img width="80%" alt="Budget Tracker Img-2" src="https://user-images.githubusercontent.com/98120553/174515370-be79af0a-9e33-4a69-8118-eaef945ffc22.png">
<img width="80%" alt="Budget Tracker Img-3" src="https://user-images.githubusercontent.com/98120553/174515377-ea4a6bfc-fbac-446e-8a2a-d3a0559f1bf3.png">
<img width="80%" alt="Budget Tracker Img-4" src="https://user-images.githubusercontent.com/98120553/174515595-8f0a2775-82c6-4382-ac9f-ad8b9ae66b15.png">




## User Story

This PWA Appplication could become very useful for the users alowing them an easy way to track their money from anywhere in the world. Also, it is very important that this PWA will allow them to access that information at any time. This application features an offline functionality which could become very crucial when handling the financial information of the users. Especialy when the customers are traveling and need to track their budget in a different time zones with or without the access to the internet.



## Acceptance Criteria

```md
GIVEN a Budget Tracker without an internet connection
WHEN the user inputs an expense or deposit
THEN they will receive a notification that they have added an expense or deposit
WHEN the user reestablishes an internet connection
THEN the deposits or expenses added while they were offline are added to their transaction history and their totals are updated
```




## Getting Started

Revisit the following lessons to complete this challenge:

### Offline Functionality

You’ll need to use IndexedDB to add offline functionality. Review Module 18: NoSQL, Lesson 4: Add Offline Persistence with IndexedDB as a refresher on how to add this to your application.

You’ll also need to add a service worker to your application. Review Module 19: Progressive Web Applications (PWA), Lesson 4: Using Service Workers as a refresher on how to add this to your application.

> **Rewind:** The Food Festival application that you created in this module's lessons did not include an Express.js server, so you used the `webpack-dev-server` npm module to test the service worker with an HTTPS-enabled server.
> 
> For this Challenge, however, you aren't using webpack, but you do have an Express.js server provided to you in the starter code. Remember that Chrome DevTools makes it possible to test service workers on localhost in development. Simply click on the Application tab in the tools, then select Service Workers from the left hand navigation.

> **Important:** You should add both of the files to handle this functionality to the `public/js/` directory of your application.

Once you’ve updated the existing budget tracker, it should provide the following functionality:

* The ability to enter deposits offline.

* The ability to enter expenses offline.

* Offline entries should be added to the tracker when the application is brought back online.



This application is deployed to Heroku.

### Web Manifest

Because this will be a mobile-first application, you’ll also need to add a web manifest to your application with the app’s metadata to let users’ devices know what they’re installing and how the app should look on the home screen.

This `manifest.json` file for this project will contain the following properties:

* `name`

* `short_name`

* `icons`

* `theme_color`

* `background_color`

* `start_url`

* `display`

> **Important:** In the module project, you used webpack to create the `manifest.json` file. For this application, you’ll need to create it manually and add it to the `public/` directory of your application. You can also review **Module 19: Progressive Web Applications (PWA), Lesson 5: PWA** as a refresher on web manifests.

### Deployment to Heroku Using MongoDB Atlas

Finally, the budget tracker has a server and uses MongoDB as its database, so you’ll need to deploy this application to Heroku using MongoDB Atlas. To review this process, look at Module 18: NoSQL, Lesson 5: Add Mongoose Validation, specifically 18.5.5: Deploy to Heroku.


## Source
Google Search</br>
heroku.com</br>
mongodb.com</br>
