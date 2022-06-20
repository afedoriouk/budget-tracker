# Budget Tracker Progressive Web Applications (PWA) Project 19
https://budgettrackerbt.herokuapp.com/

The following image shows the web application's appearance and functionality:
<img width="80%" alt="Budget Tracker Img-1" src="https://user-images.githubusercontent.com/98120553/174515359-61082ca3-be4e-4cfa-a1d6-0262f2a230d3.png">
<img width="80%" alt="Budget Tracker Img-2" src="https://user-images.githubusercontent.com/98120553/174515370-be79af0a-9e33-4a69-8118-eaef945ffc22.png">
<img width="80%" alt="Budget Tracker Img-3" src="https://user-images.githubusercontent.com/98120553/174515377-ea4a6bfc-fbac-446e-8a2a-d3a0559f1bf3.png">
<img width="80%" alt="Budget Tracker Img-4" src="https://user-images.githubusercontent.com/98120553/174515595-8f0a2775-82c6-4382-ac9f-ad8b9ae66b15.png">




## User Story

This PWA Appplication could be very useful for the users alowing them an easy way to track their finances from anywhere in the world. Also, it is very important that this PWA will allow them to access that information at any time. This application features an offline functionality which could be very useful when handling the financial information of the users. Especialy when the customers are traveling and need to track their budget in a different time zones with or without the access to the internet.



## Features of the Budget Tracker Progressive Web Applications (PWA) 

```md
Access the Budget Tracker without an internet connection.</br>
Update the balance and receive notifications about the changes.
```
### Offline Functionality

This application utilizes IndexedDB to add offline functionality.</br>
Also, this PWA using service worker to update data on the locar server.</br> 
Chrome DevTools makes it possible to test service workers on localhost.</br>
Both files are located in the `public folder`
This application is deployed to Heroku.

### Web Manifest

Web manifest is added to the application. The `manifest.json` file includes the following properties:

* `name`
* `short_name`
* `icons`
* `theme_color`
* `background_color`
* `start_url`
* `display`

### Deployment to Heroku Using MongoDB Atlas

The budget tracker has a server and uses MongoDB. The application is deployed to Heroku using MongoDB Atlas. 

## Source
Google Search</br>
heroku.com</br>
mongodb.com</br>
