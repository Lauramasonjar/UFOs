# UFOs

## Overview of Project
We need to build a **dynamic webpage** that displays UFO sighting information for the upcoming annual gathering of UFO enthusiasts in McMinnville, Oregon.

## Purpose

 The purpose of this project is to display data by adding filters to the table which lets users refine their search on more than one level.  

## Requirements
The webpage contains the following:
-   Interactive filters for searching criteria on date, city, country, and shape.
-   Brief article and its summary.
-   An attention-grabbing header with a refresh page link.
-   Visually appealing design of overall presentation of the data.

![UFOs](https://github.com/Lauramasonjar/UFOs/blob/main/images/website_header.png)

## Background 
For this project we are using **JavaScript** as the primary coding language. JavaScript (JS) is a scripting language, primarily used on the Web. It is used to enhance HTML pages and is commonly found embedded in HTML code. JavaScript is an interpreted language. Thus, it doesn't need to be compiled. JavaScript renders web pages in an interactive and dynamic fashion.

## Resources

- **Data Source:** JavaScript list [data.js](js/data.js)
- **Software:** VS Code and Chrome Developer Tools.
- **Languages:** JavaScript, HTML, CSS and Bootstrap 3
  - The table is built by inserting **JavaScript** into HTML page. [app.js](js/app.js).
  - **HTML** to build the webpage [index.html](index.html).
  - **CSS** and **Bootstrap** to build and style the page [style.css](static/css/style.css)
  - **Chrome Developer Tools** to test the code.
- **Dependencies:** D3(Data Driven Document)- We can Build a real-world, custom, interactive and beautiful data visualization from scratch using D3.

## Results

The raw data from the JavaScript array is displayed in a dynamic table where end-users can filter the data on multiple criteria such as **date**, **city**, **state**, **country** and **shape** of UFO sightings. 
The filter input box is suggesting to the end-user how search criteria should be entered by using text values in it. For example, date should be entered in format as in 1/10/2010 – with forward slashes and without the extra 0 before day and month. City, state, and country should be entered in lower case.

![UFOs](https://github.com/Lauramasonjar/UFOs/blob/main/images/filter_boxes.png)

#
When the user types the criteria in the multi-filter cells and then presses enter the table displays only rows that match the user input. From the picture below we can see only data that has been filtered based on the user input.

![UFOs](https://github.com/Lauramasonjar/UFOs/blob/main/images/filter_output.png)

# 
To reset the filter, there are two options: 1) The user can either clear input manually by deleting the input cell by cell or 2) the user can click the refresh link *UFO Sightings* that can be found at the top left corner of the page. After the filter is cleared, the user can use the filter cells again.

![UFOs](https://github.com/Lauramasonjar/UFOs/blob/main/images/refresh_button.png)

## Summary

This webpage does give a great overview of UFO sightings in the US, but it does have a few shortcomings. 

- Instead of "UFO Sightings" reset link, we can add some functions which will reset the page automatically. It could also provide some "TOP" and "BOTTOM" functions to scroll the page up and down to make it more user friendly as the table displays larger amounts of data.

- It does not have the functionality to add live data. 

- The data that is a part of the "data file" will stay the same unless and until someone changes it.


### Recommendations for further analysis

- **Input data.** 
  - By Adding code that will convert all letters to lower case from user input. For example, no matter which format the user used to type “CA” or “Ca” instead of “ca”, the code will still be able to process and find the results.
  -  We could also add some functinality that will change the user input to exact keys which will match the data. For example, if the user types "st.louis" then it will automatically change it to St.Louis or "mo" to "MO".

- **Adding a drop down-menu from the filter.**
  -  We could add a drop-down menu to the filters for faster selections instead of guessing and exploring the options.
