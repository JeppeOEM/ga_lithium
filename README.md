
## Description

This is my exam project from the machine learning and artificial course on KEA, the project was created as a group work between me and 2 other students.

The project evolves Snake playing agents using a untrained neural network and a custom made genetic algorithm. 
The neural network takes the current game state (e.g., danger in front/left/right, food direction) as input and produces action scores, which determines direction of next move, using tanh activations (ranging from -1 to 1). Agents are evaluated using a custom made fitness function based on survival, exploration and apples eaten. The genetic algorithm selects the best-performing networks each generation and creates a new population through crossover and mutation, allowing the agents to gradually improve their Snake playing abilities completely without gradient-based training.

The repository also includes testing code for experimenting with different parameters and producing Matplotlib plots of performance over generations, helping tune the evolutionary process.
