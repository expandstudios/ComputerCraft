ComputerCraft
=============

Minecraft ComputerCraft scripts and programs.

# Turtle Swarm API

Consists of:
- Swarm Base (Computer)
-- TurtleSwarm API (autoloaded)
-- tswarm program (check status etc)
- Swarm Turtle
-- Turtle Swarm API Role (startup program installed by Swarm Base and initiated)

Totally OO Turtle Swarm API to allow creation of specialised turtles easily.
New Roles should easily be added / loaded into the Turtle Swarm.

## Swarm Base 

- Check and Update Turtle Swarm from Computer
- Check turtle(s) status (job status, error, idle etc)
- Update turtle(s) with new role (turtle comes to computer for updating of software)
- Get turtle options
- Give turtle instruction
- Set turtle base co-ordinates

## Swarm Turtle

- Come home to base when idle
- Report any errors