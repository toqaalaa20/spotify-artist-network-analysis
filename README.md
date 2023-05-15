# Spotify Artist Network Analysis

This repository contains a Python notebook that focuses on performing a network analysis of related artists using the Spotify API. The main objective is to explore the connections between artists based on their related artists and visualize this network for further analysis.

## Summary

The notebook consists of the following sections:

1. **Spotify API Setup**: Imports necessary libraries and sets up the Spotify API credentials.

2. **Searching for an Artist**: Utilizes the Spotify API to search for an artist named 'Abdel Halim Hafez'. Retrieves various artist information, including their name, ID, popularity, genre, and number of followers.

3. **Retrieving Related Artists**: Retrieves the related artists of 'Abdel Halim Hafez' using the Spotify API. Presents information about the top 20 related artists.

4. **Building the Artist Network Graph**: Constructs an artist network graph using the networkx library. Applies a popularity threshold to filter out less popular artists. Reads artist names from the 'artists.txt' file, searches for each artist, and adds them to the graph if they meet the popularity threshold. Establishes connections between artists and their related artists in the graph.

5. **Analyzing the Graph**: Performs graph analysis by determining the number of connected components in the network. Presents a table displaying the degree distribution of nodes within the graph. Visualizes the graph using networkx and matplotlib.

## Repository Contents

- **notebook.ipynb**: The Python notebook containing code, explanations, and step-by-step instructions for interacting with the Spotify API and creating the artist network graph.
- **artists.txt**: A text file containing a list of initial artist names used in the process of creating the network graph.
- **README.md**: This file, providing an overview and description of the notebook and its contents.
