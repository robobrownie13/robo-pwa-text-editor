/_robo-pwa-text-editor_/

# Progressive Web Applications (PWA) Challenge: Text Editor "JATE"

[![License](https://img.shields.io/badge/license-MIT-green.svg)](https://opensource.org/licenses/MIT)

## Table of Contents

- [Description](#Description)
- [Usage](#Usage)
- [Installation Instructions](#Installation)
- [Contributions](#Contributions)
- [License](#License)
- [Questions](#Questions)

## Description

Just Another Web Application or J.A.T.E. is a single-page Progressive Web App (PWA) that runs in the browser. It incorporates various data persistent techniques and works offline, ensuring uninterrupted functionality. The application features a client-server folder structure and is bundled using webpack. Content entered in the text editor is automatically saved in IndexedDB, allowing for retrieval when reopening the application. The app provides an Install button for desktop icon download and registers a service worker using workbox, enabling pre-caching of static assets.

## Usage

To use this text editor application, navigate to the root directory and run npm install to install the dependencies. Next, run npm start to start the backend server and the client. The JavaScript files are bundled using webpack, and necessary plugins generate an HTML file, service worker, and manifest file. IndexedDB creates immediate database storage upon opening the editor, saving entered content automatically. When reopening the application, the content is retrieved from IndexedDB. Clicking the Install button allows you to download the web app as a desktop icon. You can also interact with the deployed application at the following link:

https://robo-pwa-text-editor-96edc2e65cb1.herokuapp.com/

## Installation

Using the npm install command in the terminal will allow the package json to download the necessary node_modules for this project. This will then bubble up into the server and client folder to download their necessary npm packages and node_modules.

## Contributions

If you have any suggestions for how to improve this project, send an email to easorj@gmail.com.

## License

For information on MIT, follow this link: [MIT](https://opensource.org/licenses/MIT)

## Questions

Contact me at easorj@gmail.com

You can also view my profile: [robobrownie13](https://github.com/robobrownie13)
