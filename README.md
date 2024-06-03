# BreedSeeker: Discover Your Perfect Breed

## Overview
BreedSeeker is an interactive web application designed to help users discover different dog breeds. By integrating with The Dog API and the YouTube Data API, the application provides detailed information about various dog breeds along with related videos, offering a rich informational experience.

## Features
- **Dynamic Content Update:** Utilizes JavaScript to manipulate the DOM and dynamically update content based on user interactions.
- **Web API Integration:** Fetches data from The Dog API and the YouTube Data API to display breed information and related videos.
- **WebSocket Functionality:** Enables real-time updates through WebSocket connections.
- **Custom Scrollbar:** Implements a custom scrollbar for a better user experience.
- **Responsive Design:** Ensures a seamless experience across different devices and screen sizes.
- **Animated Elements:** Includes an animated dog element to enhance user engagement.

## Project Structure
The project consists of the following key files and directories:
- `index.html`: Contains the HTML structure of the web application.
- `styles.css`: Includes the CSS styles for the web application.
- `app.js`: Contains the client-side JavaScript code.
- `server.js`: Contains the server-side code using Express.js and WebSocket.
- `README.md`: Provides information about the project.

## Getting Started

Node.js and npm installed on your machine.
ensure you installed this modules because if not you can encounter an error
- `npm init -y`: Contains the HTML structure of the web application.
- `npm install ws`: Includes the CSS styles for the web application.
- `app.js`: Contains the client-side JavaScript code.
- `npm install express`: Contains the server-side code using Express.js and WebSocket.
- `npm install axios `: Provides information about the project.

── DOGS\
    ├── node_modules\
    ├── public\
    │   ├── app.js
    │   ├── index.html
    │   ├── loop.mp4
    │   ├── styles.css
    │   ├── sample.mp4
    ├── package-lock.json
    ├── package.json
    ├── README.md
    └── server.js


### Running the Application

1. Start the server:
    ```sh
    node server.js
    ```

2. Open a web browser and go to `http://localhost:3000`.

### Usage

- Enter the name of a dog breed in the search box and click "Fetch Breed by Name" to see detailed information about the breed along with related videos.

