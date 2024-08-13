# PWA-editor

## Overview

This project is a browser-based text editor designed as a Progressive Web App (PWA). It allows users to create and edit notes or code snippets with or without an internet connection, ensuring data persistence and offline functionality. The app leverages IndexedDB for data storage and supports multiple data persistence techniques to ensure reliability across different browsers.

## Features

- **Offline Functionality**: The application works without an internet connection, thanks to the service worker and IndexedDB.
- **Data Persistence**: Uses IndexedDB for storing and retrieving notes or code snippets, with fallback methods for redundancy.
- **PWA Compliance**: Features include offline functionality, service worker registration, and app installability.
- **Webpack Bundling**: JavaScript files are bundled using Webpack, and the app includes a generated HTML file, service worker, and manifest file.

## Installation

1. **Clone the Repository**:
   ```bash
   git clone <repository-url>
   cd <repository-directory>
   ```

2. **Install Dependencies**:
   ```bash
   npm install
   ```

3. **Run the Application**:
   ```bash
   npm run start
   ```

4. **Build the Application**:
   ```bash
   npm run build
   ```

## Usage

1. Open the text editor application in your browser.
2. The application will automatically create an IndexedDB database for storing your content.
3. Enter content in the editor and click away from the editor window to save content.
4. Reopen the editor to retrieve previously saved content from IndexedDB.
5. Click the "Install" button to download the web application as an icon on your desktop.

## Deployment

Deploy the application to Render by following the [Render Deployment Guide](https://coding-boot-camp.github.io/full-stack/render/render-deployment-guide). Ensure that the `.npmrc` file is included for proper deployment.

## Acceptance Criteria

- **Client-Server Structure**: The application should have a client-server folder structure.
- **Webpack Bundling**: JavaScript files must be bundled using Webpack.
- **Generated Files**: Ensure a generated HTML file, service worker, and manifest file are present.
- **IndexedDB Functionality**: Verify that IndexedDB is used for data storage and retrieval.
- **Service Worker**: Ensure the service worker is registered and static assets are pre-cached.
- **PWA Installation**: The application should be installable as a desktop icon.


## Mock-Up

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.]
![image](https://github.com/user-attachments/assets/545b8a09-5780-49e7-bf53-8fa2d740636d)
![Uploading image.png…]()



## Links

Link to my deployed website: https://pwa-editor-7qkr.onrender.com/ 

## License

This project is licensed under the MIT License.
