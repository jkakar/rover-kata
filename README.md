# Rover Kata

We are developing the software to drive rovers on other planets, on strangely
rectangular shaped mesas.

You are provided with the following items:
the size of the mesa (width * height)
And then, several rovers, for each:
initial starting point (x, y)
the direction (N,S,E,W) it is facing.
a sequence of commands

The commands are F to move the rover forwards and L or R to turn 90 degrees
left or right.

The output should be the new position and facing for each rover, separated by
single spaces e.g. 1 1 W

An example file...

```
5 3
1 1 E
RFRFRFRF
3 2 N
FRRFLLFFRRFLL
0 3 W
LLFFFLFLFL
```

Once you've completed this... there is a change...

Alert! Robots are being lost falling off the edge of the Mesa!

To stop this, all robots are now fitted with scent markers to mark where a
robot leaves the Mesa and in which direction

A robot that is instructed to move off the Mesa where another robot has
previously been lost will ignore the order
