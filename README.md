### README.md Content

---

# Modified Game of Life by Samuel Lopez and Jesus Iniesta

## Overview

This repository contains a unique twist on Conway's Game of Life, designed by Samuel Lopez and implemented by Jesus Iniesta. The game incorporates genetic codes, mutations, and inheritance into the cellular automata model, offering a more dynamic and complex simulation.

## Play Online

You can play the game online here: [Modified Game of Life](https://gsusi.github.io/modified-game-of-life/)

## Features

### Genetic Code Representation
- Each cell has an 8-bit genetic code.
- Each bit in the genetic code determines whether the cell survives or dies based on the number of neighbors it has, ranging from 0 to 7.

### Mutation Mechanism
- Each cell has a 1% chance to mutate during each iteration.
- A mutation flips one random bit in the cell's genetic code.

### Inheritance
- When a new cell is born, it inherits the genetic code from one of its neighboring cells that caused its birth. The parent cell is chosen at random.

### Initial Conditions
- The grid initializes with a random distribution of cells.
- Each cell starts with a random genetic code.

## Installation and Usage

1. Clone this repository:  
   ```
   git clone https://github.com/gsusI/modified-game-of-life.git your-repo-name
   ```
2. Navigate to the repository folder:  
   ```
   cd your-repo-name
   ```
3. Open `index.html` in your web browser.

## Contributing

Feel free to fork this repository, create a feature branch, and submit a pull request.

## License

This project is open-source, under the MIT License.
