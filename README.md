# Goals

- Interesting Story
    - Character growth
    - Relationship development
    - World development
    - Satisfying conclusion
    - Influences on the world
    - Consequences (caused by player or otherwise)
        - Core design choice: failure is permitted, and does not end the game or rewind time. Instead you fail forward, and this influences the final ending 
    - Undetermined story
        - Must be randomly generatable
        - Must be concludable – and must conclude nicely
        - Must keep track of interesting/important story threads

- Generated music
    - Motifs tied to story elements

- Vibe/aesthetic
    - Solarpunk ??? :eyes:



Story Engine:
I propose that we track story with several threads, and using those threads and their history, generate new goals and choices for the player. We continue this process until the threads all feel nearly resolved, and then produce one final goal that resolves all the threads



# Specs

Story Engine API kinda:
- Given the current state of the story, generate new goals
    - A new goal should preferably touch multiple story threads. It should cause progression in multiple areas at once.
- When a goal is completed
    - Update the PC, NPCs, and World accordingly

Goal:
- Like a Quest.
- TODO: is this more like a contained episode of a show? The current Goal is always resovled before starting the next? OR, would the player have several goals at a time and pick which one to focus on

Story State:
- Goals
- Achievements
- PC state
	- Beliefs
	- Abilities
	- Psychology
	- Limitations (e.g. doesn’t like or trust a person)	
- NPC Goals + character state
    - Relationship with PC is an important thing to track
- World state




# Brainstorming

What are the plot hooks?

- An ancient evil has arrisen and You must head out to stop it!
- You are a renegade ship captain, and must lead a run-and-gun resistance and state building enterprise
- You are a scientist/magician and have decided to take over the world. You must manipulate, conspire, and seduce allies into assisting in your plans
- You are a tired poet, who seeks beauty in the world while fighting down internal fears


Interesting actions:

- Leading people. Strategy. Growing power. Re-learning that groups of people are hard to work with
- Laying intricate plans and watching them succeed
- Moving in a satisfying way
- Combat – but who are you fighting?
- Constructing beauty
- Changing the world, resolving tension
- Discovering and solving mystery
- Defeating enemies
- Turning enemies into friends
- Self discovery – but a game about finding fun seems like a bad game
- Creating and watching relationships – c.f. rimworld
- Watching your own character grow
- Gaining power!
- Gaining power by losing another kind of power!