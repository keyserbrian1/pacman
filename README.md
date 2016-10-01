
Pac-Man Javascript implementation
=====================

Objective
---------

To recreate the behavior of the original Pac-Man arcade game, except with a dynamic map generator, obtained from <a href="https://github.com/masonicGIT/pacman">this repository</a>

Status
------

- Currently implements the proper ghost pathing behaviors, including the "up is actually up-left" bug for ghost target square determination.

- Implements rudimentary sounds and graphics, taken from the original arcade machine.

- Does not implement the one-way to ghost portions of the map, due to procedural map generation, and does not properly implement the timings for ghosts leaving the ghost house. A simplified, timer-based method is used in its place.

- Properly implements the switch between "chase mode" and "scatter mode", causing deterministic but difficult-to-predict ghost behavior.

- Implements the proper progression of bonus fruit. Does not implement the screen-bottom level drawing code, so does not have the level 256 glitch.

- Implements the proper speed of ghosts and Pacman, using the same formulas as the arcade machine.