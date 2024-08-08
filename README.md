# Text Master Application

## Project Description
Our task is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. It will feature various data persistence techniques as redundancy in case of unsupportive browsers and will function offline.

## Technologies Used
- JavaScript
- IndexedDB
- idb package
- Webpack
- Service Workers
- Workbox
- Render for deployment

## Installation and Setup
1. Clone the repository and navigate to the project root directory.
2. Run `npm install` to install dependencies.
3. Run `npm run start` from the root directory to start the backend and serve the client.
4. Ensure that your JavaScript files are bundled using webpack.
5. Ensure your webpack plugins generate HTML, service worker, and manifest files.

## Features
- Ability to store and retrieve data using IndexedDB.
- Next-gen JavaScript compatibility.
- Automatic saving and retrieval of content in the text editor.
- Install button for desktop icon download.
- Service worker registration using Workbox.
- Proper build scripts for deployment to Render.

## Usage
1. Open the text editor web application.
2. Enter content and click off the DOM window to save to IndexedDB.
3. Reopen the text editor to retrieve saved content.
4. Click on the Install button for desktop icon download.
5. Ensure registered service worker pre-caches static assets.

# Links
 - [Text Master](https://text-master.onrender.com)

 - [Git Hub](https://github.com/seokhh10/Text_Master)

Enjoy using your Text Master Application!