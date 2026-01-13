# mujoco_arm

This repository contains files related to a MuJoCo robotic arm simulation project — including a MuJoCo Menagerie model of a robotic arm (Universal Robots UR10e) and a final project Jupyter notebook demonstrating usage and experiments with the model.

The project leverages the MuJoCo physics engine for robotics simulation. MuJoCo (Multi-Joint Dynamics with Contact) is a high-performance physics simulator widely used in reinforcement learning and robotics research.

---

## Repository Structure

mujoco_arm/
├── mujoco_menagerie/
│   └── universal_robots_ur10e/
├── FORFinalProject.ipynb
└── README.md

- mujoco_menagerie/universal_robots_ur10e/ — MuJoCo Menagerie directory for the UR10e robot arm model  
- FORFinalProject.ipynb — Jupyter notebook with simulation experiments and demonstrations

---

## Requirements

- Python 3.8 or higher
- MuJoCo (installed system-wide or via Python)
- Common Python packages:

  pip install mujoco gym numpy matplotlib

Depending on your setup, you may also need:
- mujoco_py
- mujoco-python-viewer
- jupyter

---

## Getting Started

1. Clone the repository:

   git clone https://github.com/tejasms03/mujoco_arm.git  
   cd mujoco_arm

2. Install dependencies:

   pip install mujoco gym numpy matplotlib jupyter

3. Run the notebook:

   jupyter notebook FORFinalProject.ipynb

The notebook loads the UR10e model and demonstrates simulation and visualization.

---

## What This Project Does

- Simulates a UR10e robotic arm using the MuJoCo physics engine
- Visualizes arm motion and dynamics
- Serves as a base for control, planning, or reinforcement learning experiments

---

## License

No license has been specified yet. You may want to add an open-source license such as MIT or BSD.

---

## Contact

If you have questions or issues, feel free to open an issue on the GitHub repository.

