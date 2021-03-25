# Python-Api-Challange-JDAP

## Python API Homework - What's the Weather Like?

### Intention of the Repository

This Repository has been made to summit the homework assignment for my Data Science Bootcamp at Northwestern University

Python

Student: Jorge Daniel Atuesta

March, 2021

---

### Inside of this repository

In this repository, the reader will encounter my solution to the homework assignment Python API. The repository is organized in folders and a README.md (The file you are currently reading). Here is the list of the folders and their contents so you can navigate through them.

I hope you find my work not only to be complete but to display all the knowledge learned throughout this portion of the Data Science Bootcamp at Northwestern University.1. **WeatherPy:** Inside this folder, you will have the chance to access my code for the assignment and all the output data. I encourage you to take a look inside as you will find the solution to the project and screenshots from it. Here are what's inside:

   * output_data: All images and csv files created for the project.
   * Heatmap.png: an image of the heatmap I created using Google API.
   * Heatmap_with_hotels: an image of the heatmap I created with reference points I created using Google API.
   * VacationPy-with-outputs: Here is my code for the vacation portion of the project.
   * WeatherPy-updated: Here is my code for the weather portion of the project.
2. README.MD: it's the current file you are reading. I strongly suggest navigating through it and look at the project's objective solution and analysis.

I hope you find my work not only to be complete but to display all the knowledge learned throughout this portion of the Data Science Bootcamp at Northwestern University.

---

## Python API Project

### Project's Aim

using Python requests, APIs, and JSON traversals to answer a fundamental question: "What's the weather like as we approach the equator?

#### Project's Challanges

There are two parts to this project. The first one is denominated WeatherPy, for this portion I had to create scatterplots showcasing the following relationships:

* Temperature (F) vs. Latitude
* Humidity (%) vs. Latitude
* Cloudiness (%) vs. Latitude
* Wind Speed (mph) vs. Latitude

After creating this scatterplots I had to run linear regression on each relationship, only this time separating them into Northern Hemisphere and Southern Hemisphere (

* Northern Hemisphere - Temperature (F) vs. Latitude
* Southern Hemisphere - Temperature (F) vs. Latitude
* Northern Hemisphere - Humidity (%) vs. Latitude
* Southern Hemisphere - Humidity (%) vs. Latitude
* Northern Hemisphere - Cloudiness (%) vs. Latitude
* Southern Hemisphere - Cloudiness (%) vs. Latitude
* Northern Hemisphere - Wind Speed (mph) vs. Latitude
* Southern Hemisphere - Wind Speed (mph) vs. Latitude

The second portion of the project is denominated VacationPy. For this portion I had to use jupyter-gmaps and the Google Places API to search for 'my ideal' vacation spot. For this I created a heat map that displays the humidity for every city (on part 1). After this I used Google Places API to find the first hotel for each city located within 5000 meters of the designated coordinates. Last but not least I plotted the hotels on top of the humidity heatmap with each pin containing the **Hotel Name**, **City**, and **Country**.

---

### Project outcomes

#### WeatherPy


#### VacationPy
