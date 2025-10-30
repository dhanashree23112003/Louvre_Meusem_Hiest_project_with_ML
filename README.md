## Adaptive Guard Placement Simulation

An AI-driven simulation that models how guards can adaptively position themselves in a museum to protect artifacts from thieves. The system learns from previous thief movements to predict high-risk zones and improve guard placement over time.

## Overview

This project simulates a grid-based environment where:

Thieves move intelligently toward artifacts and exits.

Guards reposition themselves adaptively after each round using heatmap analysis.

Over multiple rounds, the guards learn to protect the most vulnerable areas in the grid.

## Features

Adaptive learning of guard positions based on thief movement patterns

Weighted movement logic for thieves targeting nearby artifacts

Heatmap visualization of high-risk zones

Multi-thief simulation for realistic analysis

## Technologies Used

Python 3

NumPy for grid and distance computations

Matplotlib for visualizations
How to Run

## Clone this repository:

git clone https://github.com/yourusername/adaptive-guard-placement.git

cd adaptive-guard-placement


## Install the dependencies:

pip install numpy matplotlib


## Run the simulation:

python simulation.py

## Output

Heatmap: Shows thief movement intensity; red zones indicate high activity.

Dot Plot: Displays guard placement adapting over multiple rounds.

Console Output:

Round 1: Caught = 7, Escaped = 3  
Round 2: Caught = 9, Escaped = 1  
...
