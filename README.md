[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## W1L2 In-Class Activity

Put your notes from the W1L2 (Thurs, Jan 9) in-class activity here.

How would you describe this game world in objects?
- There are two objects, the player and the seeds being planted by the player 
What attributes and actions do these objects have?
- The player has wasd movement and the ability to plant the seeds 
- The seeds cannot be moved after being planted, there is a limited amount of seeds being planted 
How do these objects act on or affect each other?
- The player can plant seeds after pressing space 
- After 5 plants, the player can no longer place more seeds 



## Devlog
Prompt: Include the HW1 break-down exercise you wrote during the Week 1 - Lecture 2 (Jan 9) in-class activity (above). If you did not attend and perform this activity, review the lecture slides and write your own plan for how you believe HW1 should be built. If your initially proposed plan turned out significantly different than the activity answers given by Prof Reid, you may want to note what was different. Then, write about how the plan you wrote in the break-down connects to the code you wrote. Cite specific class names and method names in the code and GameObjects in your Unity Scene.


Write your Devlog here!

The exercise that breaks down the code helped a lot when writing the code. It was like a checklist of things and features that needed to be done for the game to function. It is similar to the description given in the project assignment but more detailed and suited for my own understanding. The player is controlled by the player script and their movement is updated every frame in player.update. Planting the seeds is also an action that is programmed in player.update. The UI script was connected to the UI text on the canvas. By connecting the UI text to the player inspector, the UI was able to detect and update when and how many seeds were being planted and update accordingly. The player.start was used to initiate the default amount of seeds planted and the amount of seeds remaining. After the seeds planted hits 5, the player is no longer allowed to plant seeds, pressing space will do nothing. 

This was a fun and nice practice exercise to refresh my Unity and C#. 


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
