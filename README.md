# Interview Spec

## Requirements

1. Load the JSON data for the first of the provided race IDs (`constants.ts`) into the app.
   1.1. Use your preferred data fetching library, or you can write your own data fetching code.
2. Display the data on three pages as seen in the mockups provided. These mockups are a rough guide - display the data how you like.
3. Using the "statusHistory" and "status" fields, replay a days racing. The status value is the most recent status. The app should display the relevant page for a given status. The page should display for 10 seconds before the race "enters" a new status. Statuses for each page are displayed on the mockup document. Disregard any statuses not mentioned on the next page.
4. When the current race runs out of statuses, fetch and display the next race.
