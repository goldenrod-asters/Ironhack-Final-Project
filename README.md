# Ironhack Final Project: Cycling Route Optimization Tool

## Objective:
Create a cycling route optimization tool that leverages OpenStreetMap data to generate and optimize cycling and bikepacking routes. The tool aims to provide users with personalized routes based on their preferences, stopping points, and relevant information, enhancing the overall cycling experience.<br>
### Scope limitations for MVP:
- Five European countries when developing the MVP tool: Germany, Italy, Austria, Slovenia, Czech Republic
- 10 features/variables for route optimization

## User Inputs:
Trail Type: Paved, Unpaved, Mixed<br>
Surface Type: Gravel, Dirt, Asphalt<br>
Distance: Preferred distance (per day?) for the cycling route<br>
Total Elevation: Maximum elevation gain for the route<br>
Climbing Gradients: Tolerance for steep inclines or preferences for gradual climbs<br>
Starting Point: User's initial location<br>
Destination: Planned endpoint or destination<br>
Points of Interest: Landmarks, attractions, or specific locations to visit<br>
Accommodations: different types of accommodations available along the route<br>
Dates of Travel: Travel dates to consider seasonal/weather variations<br>
Number of Days: Duration of the cycling trip<br>
Food/Drink Supply Points: Availability of supply replenishment points<br>
Additional User Inputs: TBD<br>

## Concepts to explore:
1. Graph Theory & Routing Algorithms
    - Model the road network as a graph using OpenStreetMap data.
    - Implement routing algorithms (Dijkstra's, A*) to find optimal paths.
2. Geospatial Data Processing:
    - Utilize GeoPandas, Shapely for handling geospatial data.
    - Extract relevant map features (roads, trails, points of interest).
3. User Preference Modeling:
    - Design a system to capture and model user preferences.
    - Use weighted features to influence route optimization.
4. Data Integration:
    - Integrate external data sources for weather information.
    - Incorporate user preferences and constraints into the route optimization model.
5. Route Optimization Metrics:
    - Develop metrics for optimization (distance, elevation, scenic routes).
    - Balance trade-offs based on user preferences.
6. Interactive Visualization:
    - Use Tableau for visualizing generated routes.
    - Enable users to interact with and customize routes.
7. Weather API Integration:
    - Utilize weather APIs to provide real-time and forecasted weather information along the route.
8. Machine Learning:
    - Explore ML models for personalized route recommendations.
    - Consider predicting weather impact on routes (if time allows).

## Tools and Technologies:
- Python (GeoPandas, Shapely, Requests)
- OpenStreetMap Data & Overpass API
- Tableau for Visualization
- Weather APIs (OpenWeatherMap, Dark Sky, etc.)
- Machine Learning Libraries (Scikit-Learn, TensorFlow - if exploring ML)

## Project Outcome:
A cycling route optimization tool where users can input preferences, receive optimized routes, and visualize them using Tableau. If time allows, the tool will also provide relevant information on upcoming weather conditions, enhancing the overall cycling experience.<br>



