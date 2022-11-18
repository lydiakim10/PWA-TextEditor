# PWA-TextEditor

## Description
This PWA homework assignment creates a text editor that is used in the browser, but also allows the user to install and download the application to their desktop. This application uses a package called idb, which includes the IndexedDB API. It allows users to store and retrieve data that they input into the text editor. 

## Table of Contents
* [Installation](#installation)
* [Test](#test)
* [Questions](#questions)

## Installation
In order to install this project, type "npm i" into your terminal to install the node packages. 

## Test
In order to test this project, type "npm run start:dev" into your terminal. This will ultimately create a dist folder on the client side and gives a port number for the user to use on their localhost. On the other hand, the user can simply go on the heroku link in order to use this text editor. 

When the user is in the text editor application, the user is able to type anything they desire into the text box. When the user inputs text, the text will be stored in the IndexedDB, which can be inspected in the application tab of the inspect tool. When the user refreshes the page, the inputted text will still be saved in the IndexedDB. 

If the user goes into the application tab of the inspect tool of the browser, the user is able to see that there is a service worker application and manifest application. 

If users use this application through the heroku website, they are able to click the "Install" button on the left side of the webpage that allows users to download the application to their desktop and input text through there. 

## Questions
If you have any questions, please feel free to reach out to me at:
* Github: https://github.com/lydiakim10
* Email: lydiakim10@yahoo.com

## Heroku Site
[Heroku Link](https://radiant-shore-44324.herokuapp.com/)

## Screenshots

### IndexedDB Screenshot
![IndexedDB](../../../../../C:/Users/lydia/src/PWA-TextEditor/assets/indexedDb-screenshot.png)

### Manifest Screenshot
![Manifest](../../../../../C:/Users/lydia/src/PWA-TextEditor/assets/manifest-screenshot.png)

### Service Worker Screenshot
![Service Worker](../../../../../C:/Users/lydia/src/PWA-TextEditor/assets/serviceworker-screenshot.png)

### Installed Application Screenshot
![Installed App](../../../../../C:/Users/lydia/src/PWA-TextEditor/assets/install-screenshot.png)