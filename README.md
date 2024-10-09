# Map Animation

This project demonstrates a simple map animation using the Mapbox API. The animation displays a bus route with stops between two locations, Gandhipuram and Sulur. When the user clicks the button, the map marker animates along the route, stopping at each designated bus stop.

## Features

- Interactive map powered by Mapbox.
- Animation of a bus marker moving along predefined stops.
- Button to trigger the animation of the bus route.

## Getting Started

To run this project locally:

### Prerequisites

- A Mapbox access token. If you don't have one, you can sign up and get it from [Mapbox](https://www.mapbox.com/).

### Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/map-animation.git
    ```
2. Navigate to the project directory:
    ```bash
    cd map-animation
    ```
3. Open `index.html` in your preferred code editor.

4. Replace the placeholder Mapbox access token in the `index.html` file with your own token:
    ```javascript
    mapboxgl.accessToken = 'YOUR_MAPBOX_ACCESS_TOKEN';
    ```

5. Open the `index.html` file in a web browser to view the map and start the animation.

## Usage

- Click the "Show stops between Gandhipuram and Sulur" button to start the animation.
- The marker will move along the defined bus stops every second until it reaches the final destination.

## Project Structure

