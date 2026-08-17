# Smart-Emergency-Evacuation-System

An AI-based real-time evacuation simulation that finds a safer route from a starting point to an emergency exit while avoiding walls, fire, and heat zones.

## Features

* A* pathfinding with Manhattan heuristic
* Risk-aware route planning
* Dynamic fire spreading
* Heat-zone propagation
* Automatic path recalculation
* Interactive grid-based simulation
* Real-time evacuation path visualization

## Technologies Used

* Python
* Pygame
* A* Algorithm
* Cellular Automaton
* Heap Queue (`heapq`)

## How It Works

The system represents the environment using a grid. Users can place walls, a starting point, an exit, and fire.

The AI uses **A*** to find an evacuation route. The path cost considers both distance and risk from nearby fire and heat zones.

As the fire spreads, the AI continuously recalculates the route to find a safer path.

## Controls

| Key / Action | Function       |
| ------------ | -------------- |
| `W`          | Wall mode      |
| `S`          | Set start      |
| `E`          | Set exit       |
| `F`          | Place fire     |
| `C`          | Clear grid     |
| `R`          | Reset path     |
| `SPACE`      | Pause / Resume |
| `ESC`        | Exit           |
| Left Click   | Place          |
| Right Click  | Erase          |

## Installation

Install Python and Pygame:

```bash
pip install pygame
```

Run the project:

```bash
python main.py
```

## Project Structure

```text
Smart-Emergency-Evacuation-System/
│
├── main.py
└── README.md
```

## Objective

To demonstrate how **AI-based pathfinding and dynamic risk analysis** can be used for emergency evacuation planning.

## Future Enhancements

* Multiple exits and agents
* Real-world building maps
* Machine learning-based risk prediction
* Real-time fire detection
* IoT sensor integration
* 3D evacuation simulation

## Author

**Chetan Vamsi Gangala**

## License

This project is developed for educational and academic purposes.
