# Simple Map & GPS - Dijkstra & TSP in Python 🚗📍

This project is a simple Python implementation of a map and navigation system that simulates route planning between 10 cities in East Java, Indonesia. The system uses Dijkstra's Algorithm for shortest path calculation and the Traveling Salesman Problem (TSP) algorithm for multi-city route optimization.

## Features

- Represent cities and roads as a weighted undirected graph
- Support for 3 transportation modes: car, motorcycle, and walking
- Calculates:
  - Shortest path between two cities (Dijkstra)
  - Optimal route visiting all cities once (TSP brute force)
- Includes graph visualization using matplotlib

## Cities Used (Vertices)

- Surabaya  
- Sidoarjo  
- Gresik  
- Lamongan  
- Mojokerto  
- Jombang  
- Malang  
- Blitar  
- Kediri  
- Pasuruan

## Algorithms

### Dijkstra's Algorithm
Used to find the shortest path between a starting city and destination city based on travel time or distance.

### Traveling Salesman Problem (TSP)
Finds the shortest route to visit all 10 cities once, starting from Surabaya.

## How to Run


Then follow the prompts:
- Choose transport mode (mobil/motor/jalan)
- Enter starting city
- Enter destination city

## Visualization

The program will also generate a visual graph of:
- Cities (nodes)
- Connections (edges)
- Dijkstra route in red
- TSP route in green

## Requirements

- Python 3.x
- matplotlib

Install with:


## Authors

- Iqbal  
- Adnan  
- Vanessa  

This project is part of our Data Structures course practicum.

## License

Free to use for educational purposes.
