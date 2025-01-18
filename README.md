[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity
How would you describe this game world in objects?
- There are two objects, the player and the seeds being planted by the player

What attributes and actions do these objects have?
- The player has wasd movement and the ability to plant the seeds 
- The seeds cannot be moved after being planted, there is a limited amount of seeds being planted

How do these objects act on or affect each other?
- The player can plant seeds after pressing space 
- After 5 plants, the player can no longer place more seeds 

## Devlog
The exercise that breaks down the code helped a lot when writing the code. It was like a checklist of things and features that needed to be done for the game to function. It is similar to the description given in the project assignment but more detailed and suited for my own understanding. The player is controlled by the player script and their movement is updated every frame in player.update. Planting the seeds is also an action that is programmed in player.update. The UI script was connected to the UI text on the canvas. By connecting the UI text to the player inspector, the UI was able to detect and update when and how many seeds were being planted and update accordingly. The player.start was used to initiate the default amount of seeds planted and the amount of seeds remaining. After the seeds planted hits 5, the player is no longer allowed to plant seeds, pressing space will do nothing. 

This was a fun and nice practice exercise to refresh my Unity and C#. 

## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites

## Prof comments
This Devlog was satisfactory in that it connected the break-down that you wrote to the classes and methods you wrote. However, I would like to see just a little bit more detail about your code implementation in future Devlogs. Still, this one earns full marks!

> The exercise that breaks down the code helped a lot when writing the code.

I'm glad that the break-down was helpful! I'm very interested to see if you find the HW2 break-down useful or not.

Please consider formatting your break-down activities with the hyphen '-' symbol as suggested above. Also, you can remove the prompt text. This will make it a lot easier for me to read. See the [README formatting guide here](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax).
