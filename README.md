# M5 Lab - Accessibility

## Overview
The purpose of module 5's lab was to help us learn more about web development accessibility standards and how to make a webpage more accessible. This was accomplished by taking a starter webpage and going through and making it more accessible.

## Sources and Credits
- Shane Panter: https://github.com/shanep/web-dev-starter
- WAI-ARIA basics: https://developer.mozilla.org/en-US/docs/Learn/Accessibility/WAI-ARIA_basics
- Accessible multimedia: https://developer.mozilla.org/en-US/docs/Learn/Accessibility/Multimedia

## How to run code
* To run the code open up your terminal and cd to the folder were you want to copy the repository to 

    ``` cd path/to/your/directory ```
* Once in the desired folder use the command git clone to copy the repo there 

    ```git clone https://github.com/tonyhdz24/M5-Lab-tonyhdz24```
* Then cd into the newly cloned repo

    ``` cd M5-Lab-tonyhdz24M5-Lab-tonyhdz24```

* Once in the repo folder install any dependencies the repo requires  
    ```npm install```

* Lastly open the cloned repo in your IDE open index.html and use Live Preview to view the webpage

    ``` code .```

## Accessibility Lab Answers
### Color
- The results of the test confirmed my initial thoughts that there was not enough contrast between the color of the text (black) and the background color (darkgreen).  

### Semantic HTML
1. The first time you press the `tab` it starts out as you would expect it focusing on the pages nav bar at the top. It goes through each one in the correct order. After that it then moves on as expected to the next logical element being the search boxes text field the the search boxes go button. So far navigating with the keyboard seems to work as expected and very easy todo. However after that it jumps to the bottom of the page to the media players controls then back up to to the top to the related links. This isn't very intuitive and makes for navigating the site difficult. Also the show comments button is never selected when navigating with the keyboard meaning that people using the keyboard miss out on that functionality entirely. 
2. Changed font tags used for headers to there respective semantic header tags
3. `<div class="nav"></div>` changed to the proper `nav` tag. 

### Images
- Added descriptive alt attribute to each `img` tag

### Audio Player
1. Added a transcription of the audio file 
2. Added download link as fallback 

### Forms
1. Added visually hidden label to search form
2. `label` tags linked to input using `id` and `for` attributes

### Show/Hide Comment Control
- Show comment button can now be tabbed to with keyboard. The functionality to hide/show the comments now possible using the enter button.

### Table
- Added `scope` attribute to `th` and `td` tags to establish relationship between column headers and rows. 
- Added a `caption` tag to the table
- Added a descriptive `p` after table

### Other Considerations
1. Increase font size/change font.
2. Put text into `p` tags and remove `br` tags
3. Adding lang attribute to `HTML` tag
