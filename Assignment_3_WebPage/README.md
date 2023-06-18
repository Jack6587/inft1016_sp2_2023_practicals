# INFT1016 WebPage.html

Name: Jack Klenke
Student ID: 110349473

# Important Information and Synopsis

This website is designed to display the information covered in Assignments 1 and 2 for Information Technology Fundamentals. This website utilises .html, CSS and JavaScript code.

## Features of the website
**Image Display** - 5 buttons are situated below an image at the top of the web page. These buttons correlate with an image of a type of tree. There is a default image that begins when the user opens the page, but that can be changed as desired

**Toggle Theme Switch** - The website utilises both a light and a dark theme. This can be used interchangeably by pressing the "Toggle Theme" button situated at the top of the page. The user's choice is stored in "localStorage" to remember, if the user chooses to refresh or close the page.

**Username Changing** - The user can change the greeting at the top of the page at any time. By clicking the "Apply!" button, text below the entry box displays the word entered. 

**Clock/Time Display** - Upon loading the website, there is a date and time display that correlates with the current time and date of the user.

## HTML
The HTML is designed for the general function and display of the webpage. It provides the general formatting for the website (such as the type of text - header, etc.). It is responsible for the display and foundation for each of the buttons - seen in lines such as "<button onclick="toggleTheme()">Toggle Theme</button>". The HTML text provides the display for the user input and date and time, including the "Enter your name!" text, the "Apply!" button and the text "Hello, <User>!". It also provides the JavaScript code used to make the buttons and functions work.

## JavaScript
**Toggle Themes** - The JavaScript for this website assists the user in switching between themes. Once the user has chosen a theme, it is remembered in local storage and is saved if the user were to refresh or reopen the page.

**Name Input** - While the HTML is responsible for primarily the text for the name input, the JavaScript is responsible for how it works - it uses an "event listener" to monitor when an input occurs. When it does, it prevents the web page from reloading and updates the greeting. It also checks "localStorage" to see if a name has already been entered. If this is the case, it displays that same name.

**Image Switching** - The image switch function takes a URL and a caption as parameters. It gathers this information from the HTML text.

## CSS File
The CSS file contains two collections of variables for colour on the WebPage, known as ":root" and 'data-theme="dark'". They contain variations of the same colours. It then provides some settings on its design, including the size of fonts and margins.
