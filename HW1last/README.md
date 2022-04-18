# Weekly Schedular with Some Random Suggestions

This Weekly Schedular app developed by using Python(Django) for server side and HTML,JavaScript for FrontEnd. 

- App Link:
https://stark-savannah-38172.herokuapp.com/

- User Guide:

Users can add activities by clicking the cell they want. After then, there will be four different alternatives that they can add activity. 
Firstly, they can add a random activity by clicking the first button.
Secondly, they can add a listen to music activity with a random suggested song with some informations related to that song, i.e. title and artist(s).
Thirdly, they can add a watching a movie activity with a random suggested movie with informations related to that movie, i.e. IMDB rating, Director, etc.
Lastly, Users can add activities that they want with user input.
If a user click again to the cell that is filled, they can clear that cell or go back to that activity.
After finishing the constructing the weekly schedule, user can click to the take a screenshot button on the bottom. After few seconds, a link will be appear right below to the Take a ScreenShot button. This link is a link to the image that Weekly Schedule.


- 3 different API is used.
I used k2maan-moviehut API for movie suggestion.
I used genius API for song suggestion.
I used The Bored API for random activity suggestion.

- Why Django is used ?
First of all, Django is a high-level Python web framework that enables rapid development of secure and maintainable websites. Handling server side issues so easy. In addition, Django can render HTML files dynamically. Moreover, Django automatically applies changes when you change something in the backend files.

- Why JavaScript & HTML is used ?
I handled almost all end-user actions with using JavaScript and HTML. I did not use outsource Javascript frameworks (e.g. React, Angular, etc.) because I want to handle issues by using pure JavaScript functions and tools. I used jQuery & html2canvas JavaScript libraries handle issues. I used them for easy to use ability of them.



