# Spec

## As a developer, run the app locally, 24/7 

### Startup

Developer starts the app via Visual Studio Debugging session.
Developer opens the app in the browser.

### Tesla API Token Management

App asks the developer to enter the Tesla API token.
Developer enters the token and confirms with button click.
App keeps the token in RAM.

### Charge Data Collection

App queries the vehicle charge states of all vehicles every minute and stores data in DB.

### Charge Data View

When DB is empty, app tells developer to come back later
When DB is not empty, app shows developer
- the number of months since data collection start and
- the total number of charge sessions since data collection start.