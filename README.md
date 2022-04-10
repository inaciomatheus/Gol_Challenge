# Solutions

This README file summarizes the changes made for achieving the proposed solutions on this challenge. The original README.md file is still on this repository renamed as README_OLD.md.

Observation: The "app.js" file on /backend/ folder has not been changed on this repository, although it has been locally for entering the *"clientId"* and *"clientSecret"* keys provided via email, for the purpose of not exposing these information.

##  First Task

For the activity of fixing the original broken frontend application, the actions/fixes applied can clearly be seen on commit ["First Task Completed (Fixing frontend application)"](https://github.com/inaciomatheus/Gol_Challenge/commit/aa8a7a9efa489f76ed5bdeddda7a98b852e12080).

In short, the changes made can be listed as below:

- Inserting missing "onClick" event on line 23 of flight-search-component.html
- Inserting missing closing `<em>` tag on line 54 of flight-search-component.html
- Changing type of input on line 62 of flight-search-component.html from button to text
- Initializing "toLocationTemplate" property, missing, on line 11 of flight-search-component.ts

*Observations:*
- *All line references above related to commit ["First Task Completed (Fixing frontend application)"](https://github.com/inaciomatheus/Gol_Challenge/commit/aa8a7a9efa489f76ed5bdeddda7a98b852e12080)*
- *Both files are located on the "/flight_booking-frontend/src/app/components/flight-search/" folder.*

## Second Task

Unfortunately, I was not able to make greater changes on the original application, due to the fact I just started learning more about the framework used for the frontend application, for the purpose of this challenge.

However, some minor changes have been made, aiming to make the application's visuals and its elements more user-friendly, even in small details, as well as to make it look more like a Gol's application.

Summarizing the changes that can be seen on commits, here are listed:
- Making sure clickable elements have the "pointer" cursor
- Adjustments in style (colors, shapes and images), aiming to achieve a "Gol's theme"
- Adjusting the "Duration" display format on "flights view", to ease user's reading

Also, just as an "possible changes" section, here are listed some changes I could not achieve this time, for more improvements on the frontend application:
- Apply "loading elements" for the user to know when the application is fetching information
- Apply dropdowns for the selection of locations
- Maintain choosen inputs on the page for the user to maintain track of process
- Develop loops and messages for wrong inputs or situations where no flights are available for the selected filters
- etc.