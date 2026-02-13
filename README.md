
⸻

🟪 Falling Blocks

A minimalist 2D survival game built in Unity to explore and understand core game development mechanics such as movement, spawning systems, collision handling, and difficulty scaling.

🔗 Play Here: https://whenommmm.github.io/falling-blocks-build/

⸻

🎯 Purpose of This Project

This project was built as a foundational learning exercise to become comfortable with core Unity concepts.

The focus was on understanding systems and mechanics rather than visual polish or production-level refinement.

It is intentionally simple in design and scope, with emphasis placed on:
	•	Core gameplay loop
	•	Physics and collision handling
	•	Procedural spawning
	•	Dynamic difficulty scaling
	•	Game state management
	•	WebGL deployment


🎮 Gameplay Overview
	•	Blocks spawn randomly from the top of the screen
	•	Spawn speed and difficulty increase over time
	•	Player must avoid collisions to survive
	•	Game ends on collision
	•	Survival time is displayed at Game Over

The objective is simple:
Survive as long as possible.

⸻

🧠 Core Mechanics

Player Movement
	•	Horizontal movement using keyboard input
	•	Screen wrap on left and right boundaries
	•	Collision detection using 2D triggers

Dynamic Difficulty System
	•	Difficulty scales gradually over 60 seconds
	•	Spawn rate increases over time
	•	Block speed increases based on difficulty percentage

Block Spawning System
	•	Random spawn positions within camera bounds
	•	Random size variation
	•	Random rotation angle
	•	Automatic destruction when off-screen

Game Over System
	•	Event-based player death trigger
	•	Survival time display
	•	Restart using spacebar
	•	Difficulty reset on restart

⸻

🛠 Built With
	•	Unity 6 (URP 2D)
	•	C#
	•	Unity Input System
	•	TextMeshPro
	•	WebGL Build
	•	Git & GitHub Pages deployment

⸻

📂 Project Structure

Assets/
│
├── Scripts/
│   ├── Movement.cs
│   ├── FallingDown.cs
│   ├── BlocksD.cs
│   ├── Difficulty.cs
│   └── GameOver.cs
│
├── Prefab/
│   └── FallingBlock.prefab
│
├── Scenes/
│   └── 0.unity
│
└── Settings/


⸻

🧩 Key Scripts Explained

Movement.cs

Handles:
	•	Player input
	•	Screen wrapping
	•	Collision detection
	•	Player death event

FallingDown.cs

Handles:
	•	Timed block spawning
	•	Spawn size variation
	•	Spawn angle randomness
	•	Difficulty-based spawn rate

BlocksD.cs

Handles:
	•	Downward movement
	•	Difficulty-based speed scaling
	•	Auto destroy when off-screen

Difficulty.cs

Static difficulty controller:
	•	Tracks game start time
	•	Calculates difficulty percentage
	•	Resets on restart

GameOver.cs

Handles:
	•	Death event subscription
	•	UI activation
	•	Survival time calculation
	•	Scene restart logic

⸻

🚀 WebGL Deployment

The game is deployed using:
	•	Unity WebGL Build
	•	GitHub Pages
	•	Brotli compression disabled for local testing
	•	HTTPS hosting


⸻


💡 What I Learned
	•	Event-driven architecture in Unity
	•	Managing static difficulty systems
	•	WebGL build and compression handling
	•	Git version control for Unity projects
	•	Hosting a Unity WebGL game online

⸻

📬 Contact

Vansh Srivastava
Email: vanshsrivastavaqa@gmail.com

⸻

