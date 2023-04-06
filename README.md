# DriveAI

## Introduction
This is a Python program that uses the Pygame library to simulate a car driving around a track. The car is controlled by a neural network that is evolved using the NEAT algorithm. The program also uses math and os libraries.

NEAT (NeuroEvolution of Augmenting Topologies) is an algorithm for evolving artificial neural networks using a genetic algorithm. It was developed by Kenneth O. Stanley and Risto Miikkulainen in the late 1990s. The algorithm evolves neural networks with a fixed number of inputs and outputs, and it is capable of discovering new structures to solve complex problems.

In NEAT, the initial population of neural networks is created randomly, and then the networks are evaluated on a specific task. The networks that perform the best are selected for breeding, and their genetic material is combined to create new neural networks. This process is repeated for many generations, gradually refining the population and improving performance on the task.

NEAT includes several innovations that make it particularly effective. One of these is the ability to create new neural network structures through a process called "innovation." This allows the algorithm to evolve more complex networks over time, as well as to reuse successful network structures in new contexts.

NEAT also includes mechanisms for avoiding premature convergence, such as "speciation," which divides the population into subgroups based on similarities in their genetic material. This helps to maintain diversity in the population, preventing the algorithm from getting stuck in local optima.

Overall, NEAT is a powerful algorithm for evolving neural networks, and it has been successfully applied to a wide range of problems, from game playing to robotics to scientific research.

## How to use
The program requires the Pygame and NEAT libraries to be installed. The NEAT configuration file is also required to run the program. All the required files are available in the repository. Once the libraries are installed and the configuration file is present, you can run the `main.py` script

## Author 
Janmejay Vyas





