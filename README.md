# Interview Spec

## General notes

- You will be provided with a base app/scaffolding to build from, just use your package manager of choice to install dependencies and run the app.
- Develop as though you are writing a production ready application. Try to write thorough, maintainable code instead of side project/sandbox code.
- Feel free to use AI autocomplete tools and Google but please no agent tools.

## Requirements

1. Load the JSON data for the first of the provided race IDs (`constants.ts`) into the app.
   1.1. Use your preferred data fetching library, or you can write your own data fetching code.
2. Display the data on three pages as seen in the mockups provided. These mockups are a rough guide - display the data how you like.
3. Using the “statusHistory” field, replay a days racing. The app should display the relevant page for a given status. The page should display for 10 seconds before the race “enters” a new status.
4. When the current race runs out of statuses, fetch and display the next race.
