
# Pacman AI Project

Welcome to the Pacman AI project, an academic exploration into artificial intelligence through a practical application. This project is designed as part of a university coursework "Artificial Intelligence" to delve into the complexities of AI by implementing intelligent agents within the classic Pacman game framework. The focus is on developing algorithms that enable the player to exhibit advanced behaviors such as strategic chasing, evading, and interacting under various game conditions. This implementation serves not only as an educational tool but also as a challenging platform to test and enhance our understanding of AI methodologies in dynamic environments.

## Project Structure

```
Pacman_AI/
├── Assets
│   ├── ghost_images    # Contains images for the different ghosts
│   └── player_images   # Contains images for the player character
├── board.py            # Defines the game board configurations
└── pacman.py           # Main game logic including AI behaviors for ghosts
```

## Project Phases

### Phase 0 - Situated Agents (Week 2)
For this phase, ensure your project environment is set up to build your own rational agents. The environment should include structures such as walls or obstacles and allow the agent to move around and accomplish specific tasks.

### Phase 1 - Moving Agents (Week 3)
Use search algorithms to solve tasks within the environment, such as navigating a maze or carrying items from one place to another. This phase allows for experimenting with both uninformed and informed search strategies. Be creative in task design.

### Phase 2 - Interacting Agents (Week 5)
Introduce interactions between agents within the environment. This could involve competitive interactions using adversarial search or cooperative tasks where multiple agents work together on a distributed task.

## Getting Started

To run this project, you will need Python and Pygame installed on your system.

### Prerequisites

- Python 3.6
- Pygame library

You can install Pygame using pip:

```bash
pip install pygame
```

### Running the Game

Navigate to the project directory and run the `pacman.py` script:

```bash
python pacman.py
```

## Game Mechanics

- **Player Controls**: Use the arrow keys to move Pacman through the maze.
- **Ghosts**: Ghosts have different behaviors and use AI to chase or evade Pacman based on the current game state.


## Contributing

Feel free to fork this project and contribute by adding new features or improving the existing game mechanics. Pull requests are welcome.

## License

This project is open-source and available under the MIT License.

## Authors
- **Mohamed Mourad Ouazghire 30005138**
- **Nadim Khneisser**
- **Vaya Parth Jitendra**
- **Dayanna Picon**
