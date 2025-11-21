# DevFest 2025 - GDG Cloud Jakarta #
Welcome to Home of Community, this is codesheet for Advance Vibe Coding: Integrating API with Firebase Studio at DevFest GDG Cloud Jakarta 22 November 2025. 
Enjoy the Sessions and keep Learn


## Initial Prompt:
```
A simple scheduling app to manage daily tasks and appointments. Key features include adding events with date and time, setting reminders, viewing a calendar, and marking tasks as complete. Use a clean, light blue and white color scheme.
```

## Create a Clock at Header
```
Prompt:  Create a clock in the middle of this area 
```
## Switch to Code Mode
1. Create a folder api, file named: reference.md inside the folder and paste below code:
```
TimeAPI.IO
https://timeapi.io/swagger/v0.99.4/swagger.json
```
2. Save the file and Switch Back to Vibe Mode

## Configure the App API
By Defaut, Firebase Studio used Localstorage to store the data, When Apps restart, all the data modification will back to default Value

```
Prompt: Create an API to Connect Frontend and Backend, use json file to store the data instead using localstorage
```
## Call API Reference
Firebase Studio Can Read API Docs with Manual Reference,We need to Specify where the API Documentation and it’s better to have API Structure
```
Prompt: (Select the Clock) Call the TimeIO API, get the reference from api/reference.md and use the time from there.
```
## Call Authenticated API 
To Read the Data from Auth API, Add additional reference auth to (.env) to let Firebase Studio use it and consume the API
```
Prompt: Call the WeatherAPI, get the reference from api/reference.md and authentication on .env.development
```




