# Web Dev Starter Code

## Overview

TODO: Write a project description

## Sources and Credits

TODO: You must credit the sources and authors of any code, libraries, or other
assets you use in your project. If you leave this section blank, your project
will be considered in violation of the Academic Honesty policy unless you truly
created everything from scratch with no outside help. If you need to use a
source that you cannot credit (e.g. a classmate's work), you must get explicit
permission from your instructor.

A simple bulleted list below is sufficient. For example:

- Bootstrap: https://getbootstrap.com/
- jQuery: https://jquery.com/
- Background image: https://unsplash.com/photos/...
- Sound effects: https://freesound.org/people/...
- Icons: https://fontawesome.com/
- Fonts: https://fonts.google.com/
- etc.

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
