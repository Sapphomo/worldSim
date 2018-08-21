# worldSim
text-based gameplay loop system for designing stories

# concept
If you have ever played a MUD -- or, Multi-User Dungeon as us old folks like to call it -- you know what I'm going for here. The major difference in this single player experience is the concept of time limits; purely enforced to force the player to try and complete certain tasks. Complete the task and a future "room" might be easier to solve or present different opportunities to trail down different storylines. Combine the idea of a MUD with an escape room and you get the idea.

I just wanted to design a storyline like this for myself, but creating a system that allows for *anyone* to create these simulated storylines is much easier than coding an infinitely recursive set of IF/THEN/ELSE loops on a personal project.

# timeline
Starting with SYSTEMS.md for laying out the necessary systems for the gameplay loop to function. I see the likely order of operations being:

- core code - what room am I in, what objects can I interact with in the room, what objects can I interact with on my person, an awareness/help injection system for informing player of task timelines and updates, a skills system for allowing an easier completion of tasks based on what was chosen in character creation.

- main loop
-- room system
-- verb system
-- object system
-- object in room / object in inventory system
-- task system
-- timeline system for counting down on tasks
-- character creation part
-- skills system

# contact

Feel free to reach out to millsley@gmail.com to talk about anything, or see what I'm working on next.
