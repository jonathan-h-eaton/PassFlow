# PassFlow
### Created for Data & Visual Analytics @ Georgia Tech by Jonathan Eaton, Serdar Aydinoglu, Wayne Fong, Vigneshwar Perumal, Jackson Schieber, and Enoch Anim-Koranteng

# Description
Soccer is by far the most popular sport in the world, and teams are increasingly looking to advanced analytics to gain a competitive advantage. In this project, our team predicts and visualizes soccer passing networks using Python and d3.js. Please note that my role focused on data mining and cleaning in Python, and other teammates completed the Markov Chain analysis and visualization. 

The app allows users to see FC Barcelona's most probable passing routes over the course of almost 2 decades. This tool has a number of possible applications. An opposing team could use it to analyze what the most common passing routes are, then use that to shape their defensive formations. They could also see what alternate passing routes FC Barcelona resorts to if a key player is removed from the equation (e.g., they are double-teamed during a given play). This would allow them to create a defensive strategy that is shaped specifically to the passing patterns of their opponents.

For a brief video overview of the app, click [here](https://youtu.be/51xKCuDWBJQ).

For a full summary of the app, select the PassFlow Poster file.

If you want to run the app yourself, follow the instructions below.

# Installation
Python 3.7 is recommended. The libraries flask, pandas, and numpy must be installed.
Also, internet connection is required. 
To setup the code, run "web_app.py" file. 
After showing "* Running on http://127.0.0.1:5000/", copy and paste the link into a browser. 
To ensure best performance, Safari and Chrome are recommended browsers.

# Execution
The app consists of only the home page. 
1. Click on a team that you would like to visualize. 
2. The chart will update with all the passes made by the players in light blue and display the best pass route in red. 
3. Clicking on a player in the best route will remove that player and generate the next best pass route.
