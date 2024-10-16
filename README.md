The Digital Mood Tracker is an interactive web application that allows users to track their moods over time. Users can log their moods by selecting from four different mood options (Happy, Sad, Neutral, and Angry), and the app will record the selected mood along with the current date. The app provides two key features:

Mood History: Displays a list of all the moods the user has logged, including the date and type of mood.
Mood Chart: A dynamic pie chart that visually represents the distribution of the user's logged moods.
The application stores mood data using the browser's localStorage, ensuring that the data persists even after the browser is closed or refreshed.

Features
Mood Logging:

Users can select from four mood options represented by emoji: Happy (😊), Sad (😔), Neutral (😐), and Angry (😡).
Each mood selection is saved with the current date and displayed in the Mood History section.
Mood History:

Displays a chronological list of the user's logged moods.
Each entry is visually styled with a color corresponding to the mood type.
Data is stored using localStorage to persist between sessions.
Mood Chart:

Displays a pie chart using Chart.js that shows the distribution of logged moods.
The chart automatically updates as new moods are logged.
Installation and Usage
Requirements:
A modern web browser (Google Chrome, Firefox, Edge, Safari, etc.).
Internet connection to load the Chart.js library via CDN.
Steps to Run:
Download or copy the provided HTML file.
Open the HTML file in any modern web browser.
The Digital Mood Tracker interface will load, and users can immediately start logging their moods by clicking on the mood icons.
The mood history and mood chart will update dynamically as moods are logged.
Files:
index.html: The main file for the mood tracker app.
Contains the HTML structure, CSS styling, and JavaScript functionality for the app.
LocalStorage Data:
The app stores mood data in the browser's localStorage as an array of objects, with each object containing:

mood: The selected mood (e.g., Happy, Sad, Neutral, Angry).
date: The date when the mood was logged.
