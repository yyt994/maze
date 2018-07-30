maze
====
例1
---
输入：<br>
command = "3 4\n0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"<br>
maze = create_maze(command)<br>
if (maze is not None):<br>
    print_maze(maze)<br>
输出：
[W]  [W]  [W]  [W]  [W]  [W]  [W]  [W]  [W]
[W]  [R]  [W]  [R]  [R]  [R]  [W]  [W]  [W]
[W]  [R]  [W]  [R]  [W]  [R]  [W]  [W]  [W]
[W]  [R]  [R]  [R]  [R]  [R]  [W]  [W]  [W]
[W]  [W]  [W]  [R]  [W]  [R]  [W]  [W]  [W]
[W]  [W]  [W]  [R]  [W]  [R]  [R]  [R]  [W]
[W]  [W]  [W]  [W]  [W]  [W]  [W]  [W]  [W]
例2
---
输入：
command = "3 4 0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"
maze = create_maze(command)
if (maze is not None):
    print_maze(maze)
输出：    
Incorrect command format.
例3
---
输入：
command = "3 4\n0,-1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"
maze = create_maze(command)
if (maze is not None):
    print_maze(maze)
输出：    
Invalid number format.
例4
---
输入：
command = "3 4\n0,1 1,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"
maze = create_maze(command)
if (maze is not None):
    print_maze(maze)
输出：    
Maze format error.
例5
---
输入：
command = "1 1\n0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"
maze = create_maze(command)
if (maze is not None):
    print_maze(maze)
输出：   
Number out of range.

