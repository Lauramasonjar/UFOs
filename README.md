UFOs
Overview of Project
We need to build a dynamic webpage that displays UFOs sightings information for upcoming annual gathering of UFO enthusiasts in McMinnville, Oregon.

Purpose
The purpose of this project is to display data by adding filters to the table which let users to refine their search on more than one level.

Requirements
The webpage contains the following:

Interactive filters for searching criteria on date, city, country, and shape.
Brief article and its summary.
An attention-grabbing header with a refresh page link.
Visually appealing design of overall presentation of the data.

IMAGE of page header here

Background
For this project we are using JavaScript as the primary coding language. JavaScript (JS) is a scripting language, primarily used on the Web. It is used to enhance HTML pages and is commonly found embedded in HTML code. JavaScript is an interpreted language. Thus, it doesn't need to be compiled. JavaScript renders web pages in an interactive and dynamic fashion.

Resources
Data Source: JavaScript list data.js
Software: VS Code and Chrome Developer Tools.
Languages: JavaScript, HTML, CSS and Bootstrap 3
The table is built by inserting JavaScript into HTML page. app.js.
HTML to build the webpage index.html.
CSS and Bootstrap to build and style the page style.css
Chrome Developer Tools to test the code.
Dependencies: D3(Data Driven Document)- We can Build a real-world, custom, interactive and beautiful data visualization from scratch using D3.
Results
The raw data from JavaScript array is going displayed in a dynamic table where end-users can filter the data on multiple criteria such as date, city, state, country and shape of UFOs sightings. Here filter input box is suggesting end-user that, how search criteria should be entered with using text value in it. For example, date should be entered in format as in 1/10/2010 – with forward slashes and without extra 0 before day and month. City, state, and country should be entered in lower case.

IMAGE of filter box here

When user types of criteria in multi-filter and then press enter then table displays only rows that matches the user input. From the picture below we can see only data that has been filtered based on the user input – that is -- State: ca, Shape: triangle and Date: 1/1/2010.

IMAGE of data table here

To resetting the filter, there are two options. User can either clear input manually by deleting input cell by cell or click the refresh link UFO Sightings that can be found at the top left corner of the page. After the filter is cleared, the user can use filter again.

IMAGE UFO sighting here

Summary
This webpage does give a great overview of UFO sightings in the US, but it does have a few shortcomings.

Instead of "UFO Sightings" reset link, we can add some functions which will reset page automatically. Also provide some "TOP" and "BOTTOM" functions to scroll page up and down to make it user friendly.

It does not have the functionality to add live data.

The data that is a part of the "data file" will stay the same unless and until someone change it.

Recommendations for further analysis
Input data.

By Adding a code that will convert all letters to lower case from user input. For example, no matter which format user used to type “CA” or “Ca” instead of “ca”, the code will still be able to process and find the results.
Also we can add some functinality that will change the user input to exact keys which will match the data. For example, if user type "st.louis" then it will automatically changed it to St.Louis or "mo" to "MO".
Adding drop down-menu from the filter.

Also we can add drop-down menu to the filters for the ease instead of guessing and exploring the options.
