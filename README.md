# Eye-Tracker

> https://hunterwarburton.github.io/EyeTracker/Eye%20Tracker.html

## DESCRIPTION
Eye shape drawn with CSS and controlled with JavaScript. CSS styling shapes html divs into ellipses and circles while javascript finds the mouse position and points the circular eye towards the mouse. Clicking on the eye also removes it.


## Features/Learning Purposes
This project demonstrates the ability of CSS to style and design elements on a webpage3


## HOW TO USE
Add these elements into the HTML page
<link rel="stylesheet" href="eye-tracker.css">

<div class="eyeHolder" onclick="remove(this)">

    <div class="ufo">
      <div class="eye-lid">
        <div class="eyes">
          <div class="eye"></div>
        </div>
      </div>
    </div>
  
  </div>

<script src="eyeTracker.js"></script> 


## ROADMAP of FUTURE IMPROVEMENTS
Code exists in the javascript file to cause the eye object to move around the page, the code has been commented out for current useability and simplicity.
The next improvement is to allow a button or command to create a new eye on the webpage.


## LICENSING

MIT License