# **Bike and Transit Route Planner Plan**

# Contributors
### Paige Williams  

## Description
A web application that helps people in Portland plan their multi-modal trips. The user is able to enter their start and end point, and how many miles they would like to bike. After entering their search, the user can see routes on a map that fit thier criteria. In future iterations I would like to add user authentication and have the user be able to save their search results. I would also like to add metrics on how many miles they biked and the carbon footprint of their route. 

Visit the code [here](https://github.com/paigewilliams/bike-transit-planner.git)

## Table of Contents
  1. [MVP](#specs-work)
  2. [Further Exploration](#specs-work1)
  3. [Wireframes](#wireframe)
  4. [Component Tree](#component)
  5. [Next Steps](#steps)
  6. [State Slices](#state)
  7. [Data Flow](#data)
  
## Minimum Viable Prototype (MVP) <a name="specs-work"></a>

* The user can enter a starting point and an ending point
* The user can enter how many miles they would like to bike
* The user can see a list of possible routes to take to get from their starting point to the end point
* The routes will be displayed in a map

#### Tools, frameworks, libraries, APIs, modules and/or other resources to create this MVP

* TriMet Trip Planner API to find routes 
* Google Maps API, Mapbox API, Leaflet or Open Street Map API to render route in a map
* React/Redux for the UI and state management
* Styled Components for styling 

## Further Exploration <a name="specs-work1"></a>

* The user can create an account and save their routes
* The user can rate their routes
* Possible analysis on the routes, such charts showing their miles biked or carbon emmissions saved from taking transit and biking

#### Additional tools, frameworks, libraries, APIs, or other resources that these additional features will require

* A database to save users and routes
* A user authentication service such as Google Auth
* D3 to create data visualizations

## Sketches and wireframes <a name="wireframe"></a>

![alt-text](https://github.com/paigewilliams/capstone-planning/blob/master/sketch.jpg)

![alt-text](https://github.com/paigewilliams/bike-transit-planner/blob/component-tree/src/assets/wireframe.png)

## Component tree (3/3/2019) <a name="component"></a>

![alt-text](https://github.com/paigewilliams/capstone-planning/blob/master/capstone-tree.jpg)

# Next steps as of 12/31/2019 <a name="steps"></a>

- [ ] Create About modal to explain app to user
- [x] Gather form input
- [x] Hide form upon submission, show result list
- [x] Encode address to place into API call
- [x] Make API call to Trimet Trip Planner
- [ ] Create graphic for loading page (I am assuming the call will be slowish)
- [x] Parse response
- [x] Display line geometry in the map (I am assuming the line is an encoded geojson)
- [ ] Add form validation (manage form with Formik)
- [ ] Add error message if there is no route
- [ ] Add user authentication and ability to save trips
- [ ] Data visualizations of trips

## State slices <a name="state"></a>

## Data flow <a name="data"></a>

