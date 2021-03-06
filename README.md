# robotCleaner

https://xopher00.github.io/robotCleaner/

This application asks for a set of instructions to give to a janitor robot. 
Instructions consist of a cardinal direction (N, S, E, or W) and the number of steps to take in that direction.
Based on these instructions, the application returns the number of unique spaces the robot has cleaned.
Spaces that the robot covers more than once are not counted to the unique space total.
The robot can only clean spaces within a set grid. The X and Y axes range from -100,000 to 100,000.

Some examples: 
```
Number of Commands: 3
Starting Point: 0 , 0
Command 1: N 1 
Command 2: W 3
Command 3: S 4
Output: 9 Unique Spaces Cleaned
```

```
Number of Commands: 3
Starting Point: -99999 , -99998
Command 1: W 3
Command 2: S 4
Command 3: E 4
Output: 8 Unique Spaces Cleaned
```

```
Number of Commands: 5
Starting Point: 1, 10
Command 1: E 9
Command 2: N 1
Command 3: W 9
Command 3: S 1
Command 1: E 9
Output: 20 Unique Spaces Cleaned
```
