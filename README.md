# Forest Fire Cellular Automaton Simulation

## Project Overview
This project is an agent-based simulation of a forest fire on a $100 \times 100$ grid implemented using Python and NumPy. The primary goal was to investigate the influence of initial forest density on fire spread and to identify the **critical density** at which the fire transitions from localized burning to spreading through the entire forest.

## Key Features
* **Cellular Automaton Model:** Implemented a simulation where each cell can exist in one of four states: Grassland (0), Tree (1), Burning tree (2), or Burnt tree (3).
* **Initial Setup:** Developed functionality to initialize the grid randomly based on a variable tree density parameter and simulate a lightning strike to start the fire.
* **Critical Density Analysis:** Performed multiple simulation runs for a range of initial tree densities (0.1 to 1.0) and plotted the resulting percentage of trees burnt to identify the critical density for widespread fire (found to be approximately 0.60 without wind).
* **Advanced Extension (Wind Modeling):** Integrated an extension to model the effect of wind on fire spread, which demonstrated that wind significantly enhances propagation and lowers the critical density (to approximately 0.50).
* **Visualization:** Used Matplotlib to visualize the grid states at each time step and generated an animated GIF of the fire's progression.

## Tools Used
* **Python:**
* **NumPy:** Essential for creating and manipulating the large $100 \times 100$ grid arrays efficiently.
* **Matplotlib:** For visualization of the grid states and plotting the density curve.
* **ImageIO:** Used for creating the animated GIF output.
