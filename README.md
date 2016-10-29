# 100DaysOfCode progress log

### Day 11: September 19, 2016 | Back to basics

* Cloned this log from [Kallaway/100-days-of-code](https://github.com/Kallaway/100-days-of-code).
* Learned about Markdown :)
* Decided to read through CodeSchool's Beginner's Guide to Web Development, because I am sure there is still lots that I don't know. I actually changed my editor from Notepad++ to Visual Studio Code after reading one chapter. New toy!

**Links:** [Beginner's Guide to Web Development](https://www.codeschool.com/beginners-guide-to-web-development)

### Day 12: September 20, 2016 | Back to basics 2

* Continued to read through CodeSchool's Beginner's Guide to Web Development: the part about Open Source is really interesting and demystifies the process of open source contribution. That's something I look forward to do, especially when I have more back-end knowledge.
* One question, the eternal one: what back-end language should I learn? What should I learn know? I started learning Python, I also remember enjoying learning Java at uni, as well as notions of PHP. I am going to stick with Python, but I also want to look into Node.js.

**Links:** [Beginner's Guide to Web Development](https://www.codeschool.com/beginners-guide-to-web-development)

### Day 13: September 22, 2016 | Matt Corby tribute page responsiveness

* Read about responsiveness on different websites
* Worked on responsiveness for my tribute page: hide the nav bar when the screen is less than 992 px wide, modified grid breakpoints
* Still work to do: hide Youtube video on small screens, insert a breakpoint in between what Bootstrap classes as x-small and small ti shift to a full 12-column layout

**Links:** 
* [Use CSS media queries for responsiveness](https://developers.google.com/web/fundamentals/design-and-ui/responsive/fundamentals/use-media-queries?hl=en)  
* [Responsive Web Design](http://learn.shayhowe.com/advanced-html-css/responsive-web-design/)  
* [W3 School's article on responsiveness](http://www.w3schools.com/css/css_rwd_viewport.asp)

### Day 14: September 24, 2016 | Matt Corby tribute page responsiveness 2

* Continued work on responsiveness for my tribute page: hide video on small screens, move title to avoid hiding Matt's face on small screens, created a smaller background image for mobile (loaded via media query)

### Day 15: September 25, 2016 | Matt Corby tribute page responsiveness 3 + Weather app

* Looked for a fix to problem of the beackground image being to zoomed in on mobile devices. Setting the html height to 100% seems to do the trick. It now works on my phone (even though the URL bar of the browser seems to be counted in the 100%...) and I got feeback that it seems fine on Windows Phone.
* Started to think about the Weather App (FreeCodeCamp challenge) and the OpenWeatherData API. This is going to be challenging but fun: first real app I am going to build!

### Day 16: September 26, 2016 | A slice of Python

* Long day at work and could not get myself to work on the Weather App but I completed a few Python exercises on CodeSchool. Bookmarked some other interesting-looking courses

### Day 17: September 28, 2016 | Python: file handling and exceptions

* Worked on some Python challenges with CodeSchool, learning about file handling and dealing with errors and exceptions
* Discovered coolors.co

**Links:** [Coolors.co](http://coolors.co/)

### Day 18: September 29, 2016 | em, rem

* Read about scalable units (em, rem) and responsive typography. Links below
* Some fixing on my quotes machine: the responsiveness is not great on mobile (absolute positioning is banned!), will use my new knowledge of media queries to sort this in the coming days

**Links:** 
* [Comprehensive Guide: When to Use Em vs. Rem](https://webdesign.tutsplus.com/tutorials/comprehensive-guide-when-to-use-em-vs-rem--cms-23984)
* [Everything I know about Responsive Web Typography](https://zellwk.com/blog/responsive-typography/)

### Day 19: October 1, 2016 | Quotes Machine responsiveness

* Further fixing of my Quotes Machine ("Food for Thought"): restructured the JavaScript code to get the height of the browser window and recalculate if the window gets resized (for example change from portrait to landscape), adequately cleaned up the CSS. Next task: dealing with the buttons getting over the quotes (because of absolute positioning)
* Making an effort (it pays) to use em values instead of pixels for padding and margins so that if someone changes the default font-size of their browser the content is displayed accordingly.

**Links:** [7 Habits of Highly Effective Media Queries](http://bradfrost.com/blog/post/7-habits-of-highly-effective-media-queries/)

### Day 20: October 2, 2016 | Python: bye for now

* Finished the Python challenges on CodeSchool. I intend to concentrate more on the front-end languages in the months to come so I'll park that for now (and probably forget a bit...)
* I intend to get back to Weather App in the following days/weeks

### Day 21-24: October 8, 2016 | Weather App: work in progress

* Finally got to work on the weather app. Had a weird bug where I could not get the data, but now working fine. It is actually quite easy to use APIs to my surprise; the project is demystifying it for me.
* The structure is in place and I know what I want to display so now it is only a matter of getting things done!

### Day 25-26: October 9, 2016 | Weather App

* Most of the main elements coming from the API are there. I restructured the HTML to put the search bar at the bottom to link the title with the weather results.
* Started adding the units toggle but it needs more work and positioning properly.
* Signed up on StackOverflow because I find so many useful answers there every time I code, so I need to save them to quickly get back to them if needed!

### Day 27-28: October 15, 2016 | Weather App

* Worked on unit switch and researched best way to submit location also via the Enter key.
* Work on positioning to be done, as well as background image, time stamp and finding a better name for this app!

### Day 29-32: October 16, 2016 | JavaScript Best Practices

* Learning lots of new and useful JavaScript concepts via CodeSchool's JavaScript Best Practices course. What I like is that it is not trying to teach completely new technical things but rather how to optimise my use of JavaScript (performance, amount of code written, etc.). I had never heard of the fall-through concept of the switch block. It can be really powerful in some situations.

**Links:** [CodeSchool - JavaScript Best Practices course](https://www.codeschool.com/courses/javascript-best-practices)

### Day 33: October 18, 2016 | JavaScript Best Practices

* Learned more about performance optimisation in JavaScript. So interesting to realise how usual code habits impact performance. I will need to practice these by improving my Quotes Machine, which takes a bit too much time to load at the moment.

### Day 34: October 20, 2016 | Weather App and JS optimisation

* Worked on the unit switch which enables users to switch between Celsius and Farenheit. Now operational and enables live switching (switch while the weather is already displayed).
* Practiced what I learned about optimisation on the Quotes Machine project but at this scale it is hard to notice any major change. This might be more useful to apply on the Weather App because of the HTTP requests, the numerous DOM changes etc. even though, again, it is not a big application.

**Links:** [Best Practices for Speeding Up Your Web Site](https://developer.yahoo.com/performance/rules.html)

### Day 35: October 22, 2016 | Weather App

* Rewrote part of the code to remove unnecessary API request for unit switch (I can just convert units myself in JS...)
* Started working on showing a weather icon, corresponding to the current weather and day/night. It is harder than I thought: there is an issue where the sunrise and sunset Unix times that I get from Open Weather Map are related to the current day in my time zone, not in the time zone of the city. So for example looking up Sydney's sunrise/sunset times does not always give the right info. So not comitting any code today.
* I am going to use Erik Flowers's icons, they look great.

**Links:** [Erik Flowers's Weather Icons](https://erikflowers.github.io/weather-icons/)

### Day 36: October 23, 2016 | Weather App

* Still stuck with the issue of eroneous sunrise / sunset data... and can't find a fiw on the internet. I need to find another way to choose day/night isons then. 
* Had a look at other people's projects and relised that I am supposed to show local weather via geolocalisation, but as someone who doesn't like websites being able to localise me I'll keep with my initial idea to enable users to type in their location or anywhere else.

### Day 37: October 28, 2016 | Error handling in JS

* Continued with CodeSchool's JavaScript Best Practice course: learned error handling, comparison sign, instanceof
* Request sent to Open Weather Map about the bug I found, I hope that it will be good news...

### Day 38: October 29, 2016 | Weather App

* Worked on the display of a weather icon depending of the weather id returned by the API. I am using [Erik Flowers' Weather Icons](https://github.com/erikflowers/weather-icons) which are brilliant. The API mapping enabled me to avoid having to assign an icon to each weather id.
* Depending on OpenWeatherMap's answer, the next step will be to display different icons for day and night time.
