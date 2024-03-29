# PageRank

## Objective
Implement an AI to rank web pages by importance using the PageRank algorithm.

## Python Version
Use Python 3.11 for compatibility with course modules.

## Features
- Estimate PageRank using the random surfer model and iterative algorithm.
- Define transition model to calculate probabilities for random surfer's next page visit.
- Sample pages to estimate PageRank based on specified number of samples.
- Iterate to calculate PageRank values until convergence within a threshold.

## Background
PageRank algorithm ranks web pages based on importance, considering incoming links and their weights. It accounts for the random surfer behavior and damping factor to handle cases like disconnected web pages.

## Usage
1. Execute `pagerank.py` with corpus directory as command-line argument.
2. Two methods available: sampling (for estimated results) and iteration (for precise results).
3. Results displayed for each page with corresponding PageRank values.

## Note
Ensure compliance with specification and avoid unauthorized code modifications or imports.
