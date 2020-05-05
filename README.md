# as-fuelapp-test

## Objectives
In this test autoSense will assess different aspect of a project development. 
### Code Quality

In order to get to know the code quality, we'll pay attention to the implementation of different points such as:
- API
- BLoC pattern
- Templating
- Naming convention / code readability 
- Code architecture

### Project Architecture
We want to see how you architecture your different directories and files in the project.

### Test Coverage
We want to see how you write your tests and how much test coverage you can get using unit tests and integration tests.

## Technical recommendation

### Users
The 2 users needed for the demo can be hardcoded user with a fake login page. Please find the details of the users under `/resources/users.json`
Be sure that the data in the backend are related to the users.

### Frontend
Technologies:
- Flutter
- BLoC pattern

You are free on the design.

### Backend
Technology: anything you want to create a REST API with JSON payloads.

We won't take look in the backend since we have no interest in it for now, it can return the hardcoded value that you find in the different resources file in this repository.
Please find the resources under `/resources`.

## App

This app is a fuel station app. We want several fuel stations pined on a Google maps and when the user tap on a pin it opens the fuel station page to display the different information.

We want 2 users :
- 1 with an electric car
- 1 with a fuel car

The pins on the map must display the stations with gasoline for the fuel car even if there are no pumps available.

The pins on the map must display the stations with charger for electric car even if there are no chargers available.

Add logo to the pin for station having chargers.


When tap on pin, it opens the station page and display:
- The opening time
- All fuels available
- How many chargers available
- The prices
- A button "Directions" that opens Google Maps with the location of the fuel station to start the GPS
