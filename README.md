# 19 Progressive Web Applications (PWA): Text Editor


## Task
The task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria.

To build this text editor, you will start with an existing application and implement methods for getting and storing data to an IndexedDB database. 
You will use a package called `idb`, which is a lightweight wrapper around the IndexedDB API. 

You will deploy this full-stack application to Heroku using the 
[Heroku Deployment Guide on The Full-Stack Blog](https://coding-boot-camp.github.io/full-stack/heroku/heroku-deployment-guide).

### Technical Acceptance Criteria: 40%

* Satisfies all of the above acceptance criteria plus the following:

  * Uses IndexedDB to create an object store and includes both GET and PUT methods

  * The application works without an internet connection

  * Automatically saves content inside the text editor when the DOM window is unfocused

  * Bundled with webpack

  * Create a service worker with workbox that Caches static assets

  * The application should use babel in order to use async / await

  * Application must have a generated `manifest.json` using the `WebpackPwaManifest` plug-in

  * Can be installed as a Progressive Web Application
