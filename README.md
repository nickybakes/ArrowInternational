# Unity Software Engineer at Arrow International
While working at Arrow International from April to September 2026, I shipped 3 games and developed various internal tools to aid with development. Because of my NDA, I cannot provide explicit details or screenshots.

# Game Mechanics and Features
- Developed in C# within the Unity game engine
- Worked with lead game designers to implement in-game mechanics and features
- Optimized game logic and asset management for Electronic Gaming Machines (EGMs)
- Worked with artists and technical artists to implement interactive and immersive game elements

# Internal Tools and Custom Unity Editors
While working on games, I would also develop tools to aid and speed up my development process. I also shared these tools with other engineers to gather feedback, find bugs, and help their processes too.

Batch File Compiling
-
- Wrote scripts to compile a game's Unity build with necessary files and data to then be deployed on the EGM
- The scripts were easily customizable for different folder structures
- The scripts logged useful information about what files were being compiled and its current progress
- Massively sped up and automated my build deployment and debugging process

Animation Event Editor
-
- Integrated character animations with game logic scripting using Animation Events
- Provided a more detailed editor for Animation Events compared to Unity's default editor
- Raw event data was parsed and displayed in a more user-friendly way so that artists could customize the events to their liking
- Animation Events allowed for better synchronization of character animations with sound effects, particles, and material changes

Sprite Atlas Asynchronous Loading
-
- Improved game load times by loading large Sprite Atlases in the background rather than on startup
- Created debug tools for tracking how long each Sprite Atlas takes to load
- Allowed for in-depth analysis on load time differences for each EGM

Batch Sprite Atlas Editor
- 
- Allowed for quickly editing and viewing the properties of large amounts of Sprite Atlas assets
- While this behavior was built into Unity's Sprite Atlas V1 assets, the behavior is not built in for Unity's Sprite Atlas V2 assets
- Reduces editing times from up to hours to just seconds
