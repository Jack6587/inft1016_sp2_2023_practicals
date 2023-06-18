# INFT1016 WebPage.html

Name: Jack Klenke
Student ID: 110349473

# Important Information and Synopsis

This website is designed to display information covered in Assignments 1 and 2 for Information Technology Fundamentals. This website utilises .html, CSS and JavaScript code.

## Features of the website
**Image Display** - 5 buttons are situated below an image at the top of the web page. These buttons correlate with an image of a type of tree. There is a default image that begins when the user opens the page, but that can be changed as desired
**Toggle Theme Switch** - The website utilises both a light and a dark theme. This can be used interchangeably by pressing the "Toggle Theme" button situated at the top of the page. The user's choice is stored in "localStorage" to remember, if the user chooses to refresh or close the page.
**Username Changing** - The user can change the greeting at the top of the page at any time. By clicking the "Apply!" button, text below the entry box displays the word entered. 
**Clock/Time Display** - Upon loading the website, there is a date and time display that correlates with the current time and date of the user.

## How to install and run
To operate this website, the user must download the "base.css" file so that the "WebPage.html" file can operate correctly. The CSS file is responsible for the display colours and the "dark" or "light" display themes that the user can switch between. This is done through two colour palettes: ":root" and "[data-theme="dark"]", which refer to the same colour name values, but with different properties (e.g. primary-color = rgb(255, 255, 255) in ":root" and rgb(0, 0, 0) in the "dark" theme. 

The JavaScript found in the .html file is responsible for the actual function of the toggle switch. It adjusts the value of the switch, setting the value of "data-theme".
