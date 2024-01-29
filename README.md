# Description
This package was created for the final project in Data & Visual Analytics @ Georgia Tech by Jonathan Eaton, Serdar Aydinoglu, 
Wayne Fong, Vigneshwar Perumal, Jackson Schieber, and Enoch Anim-Koranteng.

The project is about visualizing soccer passing networks and predicting most probable passing routes. I focused on data mining and cleaning in Python, and other teammates completed the Markov Chain analysis and visualization. 

For a brief video overview of the app, click [here](https://youtu.be/51xKCuDWBJQ).

For a written summary of the app, select the PassFlow Poster file.

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
