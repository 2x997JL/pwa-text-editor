# Text Editor Web Application
This is a text editor web application that allows users to write and save content with IndexedDB.

## Installation
To run this application, you need to have Node.js and npm installed on your computer. Once you have these dependencies installed, follow these steps:

* Run npm install.
* Run npm run start.
* In your web browser, and go to http://localhost:3000 to access the text editor application.

## Usage
Once you have the application running in your browser, you should see a client server folder structure. The JavaScript files in the application have been bundled using webpack, and webpack plugins have been used to generate an HTML file, a service worker, and a manifest file.

The text editor application supports next-gen JavaScript and still functions in the browser without errors. IndexedDB immediately creates a database storage when you open the text editor. You can enter content in the editor, and the content is saved with IndexedDB when you click off of the DOM window.

The text editor retrieves the saved content from IndexedDB when you reopen the editor. You can also install the web application as an icon on your desktop by clicking on the Install button. When you load the application, the static assets are pre-cached upon loading along with subsequent pages and static assets, thanks to the registered service worker using workbox.

## Deployment
To deploy the application to Heroku, make sure you have proper build scripts for a webpack application. You can deploy the application to Heroku using Git, Heroku CLI, or any other deployment method supported by Heroku.

## License
This project is licensed under the MIT license. See the LICENSE file for details.