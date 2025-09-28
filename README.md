# Gossip Protocol Simulation

This project is designed to model and evaluate the behavior of the Gossip and Push-Sum algorithms over various network topologies. It aims to explore the convergence time for these algorithms over full network, 3D grid, line and imperfect 3D grid network topologies across actor-based configurations.

The simulator allows users to define network sizes, choose different topologies and algorithms, and observe how information propagates across the system.

What is working:
Program successfully constructs network topologies with correctly initialized neighbors for each actor.
Simulator executes as expected for both Gossip and Push-Sum protocols.
Supports testing with varying network sizes and topologies, with precise time tracking.
Both algorithms reliably converge based on predefined convergence criteria.
