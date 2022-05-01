# JATE: Just Another Text Editor

![MIT License](https://img.shields.io/badge/license-MIT-green)

## Description

- Purpose of this project: A progressive web application (PWA) text editor that runs in the browser.
- Problem(s) the app solves: Not having a text editor that saves input in local storage and in a database so it can be accessed even after the application is closed.
- Languages used: HTML, CSS, JavaScript
- Brief description: A PWA text editor with data persistence techniques to save your inputs.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Screenshots](#screenshots)
- [License](#license)
- [Contributing](#contributing)
- [Tests](#tests)
- [Questions](#questions)
- [Links](#links)

## Installation

This app requires the installation of webpack, babel, css-loader, html-webpack-plugin, http-server, style-loader, idb, code-mirror-themes, express, concurrently, and if-env to function. All are included in the package.json files in the root, server, and client folders. They can be installed by opening an integrated terminal in the root folder, server folder, and client fold and entering the following input:

```bash
npm install
```

## Usage

When the user opens the text editor web application in their editor, they will see a client server folder structure. When they run `npm run start` from the root directory, the application will start up the backend and serve the client. When the user runs the text editor application from their terminal, they will find that the JavaScript files have been bundled using webpack. When they run the webpack plugins, they will find that they have generated an HTML file, a service worker, and a manifest file. When they use next-gen JavaScript in the application, they will find that the text editor still functions in the browser without errors. When they open the text editor, they will find that IndexedDB has immediately created a database storage. When the user enters content and subsequently clicks off of the DOM window, they will find that the content in the text editor has been saved with IndexedDB. When they reopen the text editor after closing it, they will find that the content in the text editor has been retrieved from their IndexedDB. When the user clicks on the Install button, they will download the web application as an icon on their desktop. When the user loads the web application, they should have a registered service worker using workbox. When they register a service worker, they should have their static assets pre cached upon loading along with subsequent pages and static assets.

## Screenshots

### The application being run in the browser

!["A screenshot of the application being run in the browser. There is a blue header at the top. On the left side is a black button with white text that reads "Install!". In the middle is white text that reads "Just Another Text Editor". On the right is the J.A.T.E icon, which looks like a stylized cube. Under the header is the text editor, which has a black background with line numbers in white down the lefthand side. There is an ASCII banner reading 'JATE just another text editor' in the first nine lines.](./img/jate_header_ss.PNG)

### The application being run from an icon on the desktop

!["A screenshot of the application after it has been downloaded and run from an icon on the desktop. Abovet the blue header is a hot pink bar. To the left in black text is "jate - J.A.T.E" and on the right are icons to zoom in, minimize the app, maximize the app, and close the app. There is a blue header at the top. On the left side is a black button with white text that reads "Install!". In the middle is white text that reads "Just Another Text Editor". On the right is the J.A.T.E icon, which looks like a stylized cube. Under the header is the text editor, which has a black background with line numbers in white down the lefthand side. There is an ASCII banner reading 'JATE just another text editor' in the first nine lines. Below that are two lines of inputted text, the first line reading 'console.log("hello world!") and the second reading ("This is being saved to local storage and the database!")](./img/jate_desktop_ss.PNG)

## License

This application is licensed under the MIT license.

## Contributing

If you would like to contribute to this application, please follow Creative Contribution guidelines.

## Tests

Test to see if the app can be installed.
Check if data is stored locally and in the database, even after the app is closed.

## Questions

If you have any questions:

- Email me: [meegan.r.anderson@gmail.com](mailto:meegan.r.anderson@gmail.com)
- Go to my github: [NotANewt](https://github.com/NotANewt)

## Links

- Here is the repo: [NotANewt/JATE: Just Another Text Editor](https://github.com/NotANewt/Just_Another_Text_Editor)
- Here is the pages on Heroku: [Heroku/pages](https://jate-meegan.herokuapp.com/)
