# CalWaterPolo Project

Python 2.7 is used in this project, and files with .ipynb extension should be opened with jupyter notebook to run them.

This project organizes 26 water polo game videos (important events are extracted from each game and saved as different clips, and respective json files contain event labels and times), tracks movements of players, ball, and goalies. Tracks are used to train models for objective detection and tracking. Detailed analyses are followed to enhance players' perofrmance.

# Data Organization

- function.ipynb contains main functions used for data organization
- Basically function.ipynb takes inputs (game_code, clip, option) and create image view videos with bouding boxes around players and ball. Users can choose to include trajectory in the videos. Overhead view videos of games are also provided in another function. Users can choose to only create image view, only overhead view, or side-by-side view of two videos.

# Object Detection



