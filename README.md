# A-Novel-Framework-for-Self-Correcting.
 This repository contains the prototype for a "Crisis-Driven Learning" artificial intelligence. Unlike traditional reinforcement learning, this agent does not require rewards. Instead, it learns by treating high prediction errors as logical "crises," which trigger non-monotonic belief revision to build a coherent and interpretable world model.
 📁 Project Structure

crisis-learning-ai/
├── core/                       # Core AI architecture
│   ├── belief_base.py          # Non-monotonic belief engine (Crisis Engine)
│   ├── predictive_sensor.py    # Neural network predictor
│   └── agent.py                # Main agent class
├── environments/               # Worlds for the agent
│   ├── one_d_world.py          # Original 1D learning sandbox
│   └── maze_3d/                # 3D raycasting maze environment
│       ├── raycaster.py        # First-person 3D perception
│       └── crisis_maze_3d.py   # Interactive 3D maze
├── demos/                      # Ready-to-run demonstrations
│   ├── run_1d_demo.py
│   └── run_3d_maze.py
├── assets/                     # Screenshots, diagrams
├── requirements.txt
└── README.md                   (This file)
