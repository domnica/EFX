# EFX
The algorithm for finding EFX allocations can be run directly online at https://colab.research.google.com/drive/1IDj2yAgtYGf6y9vVtfYR_-kyuhwIl6zQ?usp=sharing. 
The pseudocode and experimental results are described in the attached paper (EFX_paper.zip). 

This repository contains the following files.

- The implementation of the algorithm in main_implementation.ipynb. The program generates a random instance of valuations and finds an EFX allocation for that instance. 

- To visualize the runtime of the algorithm for n=15 agents and growing number of items (from m = 3 to m = 1050), run the accompanying notebook EFX-visualizations-15-agents.ipynb.
- To visualize the runtime for m = 10,000 items and growing number of agents (from n = 4 to n = 100), run the notebook EFX_visualizations_10k_items.ipynb.
- To visualize the runtime for n=8 agents and m = 160 items with correlated valuations, run the notebook EFX_visualizations_correlated_8_agents_160_items.ipynb.
