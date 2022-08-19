<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://mapty-shoeb.netlify.app/">
    <img src="./logo.png" alt="Logo" width="100px" height="50px">
  </a>

  <h3 align="center">Mapty</h3>

  <p align="center">
   A Map application made with JavaScript to store workouts.
    <br />
    <a href="#about-the-project"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://mapty-shoeb.netlify.app/">View Demo</a>
  </p>
</p>

<!-- TABLE OF CONTENTS -->
<details open="open">
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
  </ol>
</details>

<!-- ABOUT THE PROJECT -->

## About The Project

Mapty is a vanilla JavaScript application that interacts with the Leaflet library and display Map. This app uses modern JavaScript tools, such as Webpack to bundle the modules, and Babel to convert ES6, ES7 and ES8 back to ES5. The user can add workouts for running and cycling and these are stored via local storage.

### Built With

This app is built with pure vanilla JavaScript along with HTML and SCSS. It uses webpack as module bundler and NPM as package manager.

- [HTML](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [SCSS](https://sass-lang.com/)
- [JavaScript](https://developer.mozilla.org/en-US/docs/Web/javascript)
- [Webpack](https://webpack.js.org/)
- [NPM](https://www.npmjs.com/)

<!-- GETTING STARTED -->

## Getting Started

To get started with project just simply fork this repo or download locally on your System.

To get a local copy up and running follow these simple example steps.

### Prerequisites

Start with the latest version of NPM to avoid any errors:

- npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Get Leaflet library [Leaflet](https://leafletjs.com/)
2. Clone the repo
   ```sh
   git clone https://github.com/Shoeb-Alam/Mapty.git
   ```
3. Install NPM packages
   ```sh
   npm install
   ```

<!-- USAGE EXAMPLES -->

## Usage

1. Add workouts near to your Geo location.

2. Add workouts to bookmarks to view it later.

3. Click on workouts to see it's location.

<!-- ROADMAP -->

## Roadmap

### Proposed features

1. Ability to edit a workout.

2. Ability to delete a workout.

3. Ability to delete all workouts.

4. Ability to sort workouts by a certain field (e.g. distance).

5. Re-build Running and Cycling objects coming from Local Storage.

6. More realistic error and confirmation messages.

7. Ability to position the map to show all workouts.

8. Ability to draw lines and shapes instead of just points.

9. Geocode location from coordinates.

10. Display weather data for workout time and place.
