```markdown
# Kenya Web Map Project

This project displays an interactive web map of Kenya using Mapbox GL JS. It centers on Kenya, with a marker for Nairobi (Kenya's capital) and includes navigation controls for zooming and panning.

## Features
- Interactive Map: View a detailed map of Kenya with zoom and navigation controls.
- Centered on Kenya: The map is initially centered on Kenya's geographical coordinates.
- Marker for Nairobi: A marker is added to highlight Nairobi, with a popup displaying the city's name.
- Customizable: Easily adjust the map style, markers, and zoom level.

## Requirements
- A web browser (modern versions of Chrome, Firefox, Safari, or Edge).
- A valid Mapbox Access Token.

## Installation
1. Clone or download the project files:
   ```bash
   git clone https://github.com/your-repo/NairobiMapbox-webapp.git
   ```
2. Navigate to the project directory:
 
   ## Usage
1. Open the `index.html` file in a text editor.
2. Replace the placeholder text `'your-access-token-here'` in the following line with your actual Mapbox Access Token:
   ```javascript
   mapboxgl.accessToken = 'your-access-token-here';
   ```
3. Save the file.
4. Open the `index.html` file in a browser to view the map.

## Customization
- Center Coordinates:Adjust the map's center by modifying the `center` property in the script:
  ```javascript
  center: [37.9062, -1.286389], // Longitude, Latitude
  ```
- Zoom Level: Change the initial zoom level by updating the `zoom` property:
  ```javascript
  zoom: 6, // Adjust zoom level as needed
  ```
- Map Style: Choose a different Mapbox style by modifying the `style` property:
  ```javascript
  style: 'mapbox://styles/mapbox/streets-v12', // Other styles include 'satellite-v9', 'dark-v10', etc.
  ```

## Project Structure
```
├── index.html   # Main HTML file containing the map code
└── README.md    # Documentation for the project
```

## Preview
The map centers on Kenya and displays a marker for Nairobi:
- **Center Coordinates:** `[37.9062, -1.286389]` (Kenya's center).
- **Marker:** Highlighting Nairobi with a popup label.

## Technologies Used
- [Mapbox GL JS](https://docs.mapbox.com/mapbox-gl-js/) - JavaScript library for interactive maps.
- HTML5 and JavaScript - To build the web map.

## License
This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).

## Author
Created by **Festus Mutie**. For any questions or feedback, feel free to reach out!

## Acknowledgments
- [Mapbox](https://mapbox.com) for providing the map library and APIs.
- Open-source tools and communities for making web development accessible.
```
