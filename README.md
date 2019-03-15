# robotCleaner

https://xopher00.github.io/robotCleaner/

This application asks for a set of instructions to give to a janitor robot. 
Based on these instructions, it returns the number of unique spaces the robot has cleaned.
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
Number of Commands: 2
Starting Point: -100000 , -99999
Command 1: W 2
Command 2: S 2
Output: 2 Unique Spaces Cleaned
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
