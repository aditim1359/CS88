Map Project: Data Analysis and ML Implementations

In this project, I create a visualization of restaurant ratings using machine learning and the Yelp academic dataset. In this visualization, Berkeley is segmented into regions, where each region is shaded by the predicted rating of the closest restaurant (yellow is 5 stars, blue is 1 star). Specifically, the visualization you will be constructing is a Voronoi diagram.

In the map above, each dot represents a restaurant. The color of the dot is determined by the restaurant's location. For example, downtown restaurants are colored green. The user that generated this map has a strong preference for Southside restaurants, and so the southern regions are colored yellow.

This project introduces techniques and concepts from machine learning, a growing field at the intersection of computer science and statistics that analyzes data to find patterns and make predictions.

Here are the files in the project:

abstractions.py: Data abstractions used in the project

recommend.py: Machine learning algorithms and data processing

utils.py: Utility functions for data processing

ucb.py: Utility functions for miscellaneous and debugging

data: A directory of Yelp users, restaurants, and reviews

ok: The autograder

proj1.ok: The ok configuration file

tests: A directory of tests used by ok

users: A directory of user files

visualize: A directory of tools for drawing the final visualization
