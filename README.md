Ant Farm Simulation

Welcome to the Ant Farm Simulation! Watch a colony of ants dig tunnels, search for food, and bring it back to their nest. This interactive simulation runs in your browser using HTML5 Canvas and JavaScript.

How It Works

•	Ant Behavior: Ants start at the nest (gray area at the bottom center). They dig tunnels through the dirt (brown), search for food, and use pheromone trails to guide their movements.

•	Environment:

o	Grass: The green top row is a barrier—ants can’t dig through it.

o	Nest: The gray area at the bottom center is the ants' home.

o	Food: Purple squares represent food piles. Click anywhere to place food for the ants to find.


•	Ant States:

o	Searching (Red): Ants explore the dirt, looking for food.

o	Carrying (Blue): When an ant finds food, it turns blue and returns to the nest using a pathfinding algorithm.


•	Pheromones: Ants leave pheromone trails to mark paths to food (red hues) and the nest (blue hues). These trails evaporate over time but help ants navigate efficiently.


How to Use the Simulation

1.	Open Sim

o	The simulation starts automatically with 12 ants.

2.	Interact with the Controls (top-left corner):

o	Ants: Set the number of ants (1 to 100). Default is 12.

o	Pheromone: Adjust the strength of pheromone trails (0.1 to 10). Higher values make trails more influential. Default is 1.

o	Evaporation: Set the pheromone evaporation rate (0.9 to 1). Lower values make pheromones fade faster. Default is 0.95.

o	Restart: Click this button to reset the simulation with your new settings.

4.	Place Food:
   
o	Click anywhere on the canvas (except the grass) to place a food pile.

o	Each food pile starts with 12 pieces. Ants will collect pieces one by one until the pile is gone.

6.	Add to Your Phone:
7.	
o	To use this like an app on your phone:

	iPhone (Safari): Open the live demo, tap the share icon (square with an arrow), and select "Add to Home Screen."

	Android (Chrome): Open the live demo, tap the three-dot menu, and select "Add to Home screen."

o	Launch it from your home screen anytime!

Tips for Best Experience

•	Experiment with Settings: Try different numbers of ants or pheromone settings to see how the colony behaves.

•	Place Multiple Food Piles: Click in different spots to create multiple food sources and watch the ants form paths.

•	Watch Pheromone Trails: The colors in the tunnels show pheromone strength—red for food trails, blue for nest trails.

•	Be Patient: Ants take time to explore and find food, especially in a large area.

Troubleshooting

•	Simulation Not Loading: Use a modern browser (Chrome, Firefox, Safari). If the page doesn’t load, refresh after a few minutes.

•	Ants Not Moving: Ensure the number of ants is greater than 0. Click "Restart" to apply changes.

•	Canvas Looks Blank: Make sure you’re not zoomed out too far. The simulation should fill your screen.

About the Project

This ant farm simulation was created as a fun way to explore ant colony behavior using simple AI techniques like pheromone-based pathfinding and weighted random movement. It’s built entirely with HTML, CSS, and JavaScript—no external libraries required. The ants move smoothly thanks to interpolated rendering, making their crawling look natural.

Enjoy watching your ant colony thrive!

