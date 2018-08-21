## worldSim
text-based gameplay loop system for designing stories

# concept
If you have ever played a MUD -- or, Multi-User Dungeon as us old folks like to call it -- you know what I'm going for here. The major difference in this single player experience is the concept of time limits; purely enforced to force the player to try and complete certain tasks. Complete the task and a future "room" might be easier to solve or present different opportunities to trail down different storylines. Combine the idea of a MUD with an escape room and you get the idea.

I just wanted to design a storyline like this for myself, but creating a system that allows for *anyone* to create these simulated storylines is much easier than coding an infinitely recursive set of IF/THEN/ELSE loops on a personal project.



# timeline
Starting with SYSTEMS.md for laying out the necessary systems for the gameplay loop to function; creating project management system via PivotalTracker. Main stories to complete are:

<dl>
  <dt>core code</dt>
  <dd>
    Eventually contain skeleton for: what room am I in, what objects can I interact with in the room, what objects can I interact with on my person, an awareness/help injection system for informing player of task timelines and updates, a skills system for allowing an easier completion of tasks based on what was chosen in character creation.
  </dd>

  <dt>main loop</dt>
  <dd>
    time loop for time spent in a room before MOVING to a new one.
  </dd>
  
  <dt>room system</dt>
  <dd>
    object that contains a description, and is a container for interactable objects. Tasks (with previous completion / failure trees contained) inject themselves into a room based on previous actions in previous rooms.
  </dd>

  <dt>verb system</dt>
  <dd>
    commands for user to interact within certain room with certain objects (room first, then inventory)
  </dd>
  
  <dt>object system</dt>
  <dd>
    items within a room that if interacted with correctly, can change the state of a task's future trajectory.
  </dd>

  <dt>object in room / object in inventory system</dt>
  <dd>
    Objects you can take from a room and allow you to interact with in every room.
  </dd>
  
  <dt>task system</dt>
  <dd>
    Tasks "start" upon entrance to a certain room; likely, a bunch will start on the first room. Then if you REVIEW TASKS or something along those lines, you have a roundtime to remember all of the tasks to complete. If you don't interact with a certain task via a verb or interaction with an object by a certain time, the memory becomes hazier and the first revealed details of the task start fading away from your REVIEW TASKS remembrance. Eventually, just falls off the list and you can try to remember it; possible context clues appear in the room instead that might help you. Or if you CHECK PHONE you may see texts / calls / calendar reminders to do something.
  </dd>

  <dt>timeline system for counting down on tasks</dt>
  <dd>
    These could possibly be basic tasks to remind you to do essential functions before leaving a room - IE; put clothes on before leaving to work. If not even that is done, you get a STRONG FAIL that will have serious consequences for later tasks, may have them skip altogether and enter new situations with a negative comeuppance further down.
  </dd>
  
  <dt>character creation intro</dt>
  <dd>
    Something giving the storyline some variability based off of initial context. Also allows skills to help with tasks.
  </dd>

  <dt>skills system</dt>
  <dd>
    Skillcheck to see if you have the skills from the character creator to either bypass a task completely, lower the roundtime of completing it, or let you simply USE SKILL to not have to figure out the verb to objects needed to complete the task.
  </dd>
</dl>

# contact
Feel free to reach out to millsley@gmail.com to talk about anything, or see what I'm working on next.

# license
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

# acknowledgments
* Thanks to AOL 1.0 for keyword: games at age 10 which provided DragonRealms - a text-based massively multiplayer online RPG before there were MMORPGs with graphics. Still a few hundred players online during peak nowadays, but back then... 2500-3000, easy.
* Everyone involved in getting us to the point where computers can be used to create stories and connect people.
