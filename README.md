## Unity Tools
[OSMLoader](https://github.com/3rd-Party-Guy/OSMLoader)
Tool for generating cities using large OSM data files. Uses materials for walls/roofs and roads to create believable cities.

[Unity Blackboards](https://github.com/3rd-Party-Guy/Unity-Blackboards)
A fast and reliable implementation of a blackboard data structure. Uses key objects for fast and consistant retrieval, while also allowing you to manage access to all entries.

[Unity FSM](https://github.com/3rd-Party-Guy/Unity-FSM)
Somewhat unconventional implementation of a finite state machine. The design is data-driven, using ScriptableObjects to define both behaviour and connections.
Uses Unity Blackboards to manage state and context. Allows for modular, designer-friendly state-machine design that can easily be changed during runtime.
All behaviour and state is encapsulated and private, making debugging very easy. 

[Element-FighterZ](https://github.com/3rd-Party-Guy/Element-Fighter)
A 1v1 fighting game created using pure JavaScript. Engine architecture uses an ECS implementation. Characters, combat, and animations are defined using JSONs and loaded in dynamically,
making extension very easy and modular. I created a novel combat-collision technique using shaders and XOR operations. This allows for a fast combat system in which what you see is truly what you get.
While there are some things I would change nowadays, especially within the ECS department, I believe this project shows how I believe a game-engine should be implemented best:
- Simple
- Extensible
- Data-Driven

[Kuriotska](https://github.com/3rd-Party-Guy/Kuriotska)
Simple top-down game inspired by Vampire Survivors. Written purely in C++, using ncurses for graphics. Utilizes multi-threading and an internal ECS.
