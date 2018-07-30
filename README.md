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
[W]  [W]  [W]  [W]  [W]  [W]  [W]  [W]  [W]<br>
[W]  [R]  [W]  [R]  [R]  [R]  [W]  [W]  [W]<br>
[W]  [R]  [W]  [R]  [W]  [R]  [W]  [W]  [W]<br>
[W]  [R]  [R]  [R]  [R]  [R]  [W]  [W]  [W]<br>
[W]  [W]  [W]  [R]  [W]  [R]  [W]  [W]  [W]<br>
[W]  [W]  [W]  [R]  [W]  [R]  [R]  [R]  [W]<br>
[W]  [W]  [W]  [W]  [W]  [W]  [W]  [W]  [W]<br>
例2
---
输入：<br>
command = "3 4 0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"<br>
maze = create_maze(command)<br>
if (maze is not None):<br>
    print_maze(maze)<br>
输出：<br>    
Incorrect command format.<br>
例3
---
输入：<br>
command = "3 4\n0,-1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"<br>
maze = create_maze(command)<br>
if (maze is not None):<br>
    print_maze(maze)<br>
输出：<br>    
Invalid number format.<br>
例4
---
输入：<br>
command = "3 4\n0,1 1,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"<br>
maze = create_maze(command)<br>
if (maze is not None):<br>
    print_maze(maze)<br>
输出：    <br>
Maze format error.<br>
例5
---
输入：<br>
command = "1 1\n0,1 0,2;0,0 1,0;0,1 1,1;0,2 1,2;1,0 1,1;1,1 1,2;1,1 2,1;1,2 2,2;2,2 2,3"<br>
maze = create_maze(command)<br>
if (maze is not None):<br>
    print_maze(maze)<br>
输出：   <br>
Number out of range.<br>

