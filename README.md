# Spotify Artist Network Analysis
This Python notebook performs a network analysis of related artists using the Spotify API. The goal is to explore the connections between artists based on their related artists and create a visual representation of the network.

**Summary of the Notebook**

1- Spotify API Setup:
Imports the required libraries: numpy, networkx, matplotlib, spotipy.
Sets up Spotify API credentials.

2- Searching for an Artist:
Uses the Spotify API to search for an artist named 'Abdel Halim Hafez'.
Retrieves information about the artist, such as name, ID, popularity, genre, and number of followers.

3- Retrieving Related Artists:
Fetches the related artists of 'Abdel Halim Hafez' using the Spotify API.
Displays information about the first 20 related artists.

4- Building the Artist Network Graph:
Initializes an empty graph using networkx.
Sets a popularity threshold to filter out less popular artists.
Reads the artist names from the artists.txt file.
Searches for each artist and adds them to the graph if they meet the popularity threshold.
Connects artists to their related artists in the graph.

5- Analyzing the Graph:
Calculates the number of connected components in the graph.
Displays a table showing the degree distribution of the nodes in the graph.
Generates a visual representation of the graph using networkx and matplotlib.
