# Some Key Features for a Well Done Web App for Mobile Devices.


### **Using Table Grids On Mobile**
Here are 10 different ways to use tables in mobile view: [Table View Mobile](http://sitesforprofit.com/responsive-table-plugins-and-patterns)

**Tips:**  When breaking the columns down vertically for mobile view, a suggestion would be to have the information collapsed and only show a single header with key info and have each row exapand as user makes a selection.

### **Making It Feel App-Like**
It is important that we make our web app look and work like a native app when viewed on a mobile browser.

Here are some examples to help get an idea of what the User Interface should look like when rendered on a mobile device:

1.) [Opentest](https://www.opentest.co/)   
2.) [Bloc Dev Bootcamp](https://www.bloc.io/)     
3.) [Golang](https://golang.org/)

### **Able To Install Wepapp On Home Screen (App install Banner for webapp and a favicon for home screen shortcut)**

We want to give our user the capablitilty to install the web app to the home screen. This is done by using a web app install banner allowing for users to download the app with a home screen icon as if they are downloading a native app.

Chrome automatically displays the install banner if the following is met during development:

1.)
A Web app manifest file  
2.) A service worker registered for the website  
3.) Use of the HTTPS protocol   
4.) End user must visit twice, with a minimum of 5 mins between visits

[Click here for more detail](https://developers.google.com/web/fundamentals/engage-and-retain/app-install-banners/)


### **Disable Pinch Zoom For Webapp**

Can be done using this meta tag:

    <meta name="viewport" content="width=device-width,
    initial-scale=1.0, maximum-scale=1.0,
    user-scalable=no" />

The reason to do this is so the user has a better experience when using the webapp. It will come off as more of a native app and will hint the user that they are seeing everything they should be seeing on the screen (no need to zoom in or out)

### **Should Support Push Notifications/Offline Capablitilty (Service Workers)**

With the use of service workers we can successfully add features to a webapp that were only normally seen with native apps. Such as push notifications and offline experience.

A service worker is just a script that is run by your browser in the background, allowing for the features mentioned above.

[Click here for more details](https://developers.google.com/web/fundamentals/getting-started/primers/service-workers)
