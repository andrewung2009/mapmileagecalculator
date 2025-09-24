A web-based route planning application designed for delivery drivers to optimize their routes, calculate distances, estimated travel times, and potential earnings.

Features
Interactive Map: Built with Leaflet.js for a responsive and interactive mapping experience
Location Search: Autocomplete functionality for finding addresses using the Photon API
Route Planning: Add multiple waypoints between start and end locations
Route Calculation: Calculates optimal routes using the OSRM routing engine
Delivery Metrics: Displays distance, estimated travel time, and earnings (RM 0.60 per km)
Route Visualization: Visualizes the calculated route on the map
Summary Download: Generate and download a summary image of your delivery route
Technologies Used
Leaflet.js: Interactive maps
OpenStreetMap: Map tiles
Photon API: Location search and geocoding
OSRM API: Route calculation
html2canvas: Generating summary images
HTML5, CSS3, JavaScript: Core web technologies
How to Use
Set Start Location: Enter your starting point in the "Start location" field
Add Waypoints: Click "+ Add Location" to add intermediate stops as needed
Set Destination: Enter your final destination in the "Destination" field
Calculate Route: Click "Calculate Route" to generate the optimal path
View Results: The distance, estimated time, and earnings will be displayed
Download Summary: Click "Download Summary" to save a visual summary of your route
Running the Application
This application is a single HTML file that can be run directly in any modern web browser:

Download the delivery-planner.html file
Open it in your browser (Chrome, Firefox, Safari, Edge)
No installation or server setup required

Limitations
Earnings calculation is based on a fixed rate of RM 0.60 per kilometer
Route calculation is optimized for driving only
Location search is limited to Malaysia (bounding box: 109.5,0.8,115,5.5)
