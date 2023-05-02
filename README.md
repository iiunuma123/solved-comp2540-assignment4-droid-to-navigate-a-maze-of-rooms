Download Link: https://assignmentchef.com/product/solved-comp2540-assignment4-droid-to-navigate-a-maze-of-rooms
<br>
Write a computer program to help a droid to navigate a maze of rooms. Your program will help the droid to find the shortest direct (no repeats) path from a start room to an ending room (a room with an exit) in the maze. The input will be a maze read from a text file.​ ​The​ ​file​ ​has​ ​the​ ​following​ ​structure

<ul>

 <li>The​ ​first​ ​line​ ​contains​ ​an​ ​integer​ ​represents​ the​ ​​number​ ​of​ ​rooms​ ​in​ the​​ ​maze</li>

 <li>The​ ​second​ ​line​ ​contains​ ​an​ ​integer​ ​represents ​the​​ ​id​ ​of​ ​the​ ​starting​ ​room</li>

 <li>The third line contains an integer represents the id of the ending room (the room with​ ​the​ ​exist)</li>

 <li>The rest of the file contains the maze represented as a 2-dimensional square matrix. The row and column indices represent the room id. The data inside the matrix indicates if there is a door from one room to another room or not. For example, if maze[3][7] =1. This means there is a door from room 3 to room 7 and</li>

</ul>

if​ ​maze​ ​[4][1]=​ ​0​ ​this​ ​mean​ ​there​ ​no​ ​door​ ​from​ ​room​ ​4​ ​to​ ​room​ ​1




For​ ​instance​ ​let​ ​us​ ​assume​ ​the​ ​following​ ​maze:




The​ ​input​ ​file​ ​for​ ​the​ ​maze​ ​above​  ​is​ ​shown​ ​on​ ​the​ ​next​ ​page




<strong> </strong>

<strong> </strong>

University​ ​of ​​Windsor

School​ ​of​ ​Computer​ ​Science

Fall​ ​2017

<strong>Input</strong>​ ​<strong>File </strong>

8

0

6

1,1,0,0,1,1,0,0

1,1,0,0,1,0,0,0

0,0,1,1,0,0,0,1

0,0,1,1,0,1,1,0

1,1,0,0,1,1,0,0

1,0,0,1,1,1,0,0

0,0,0,1,0,0,1,1

0,0,1,0,0,0,1,1




<strong>Output </strong>

0,​ ​5,​ ​3,​ ​6

<strong> </strong>

<strong>Note</strong>

<ol>

 <li>Other paths such as [0, 1,4, 5,3, 6] or [0, 5, 3, 2, 7, 6] are not accepted since they are​ ​not​ ​shortest​ ​path</li>

 <li>It is possible that the maze has no solution, for example, the dorid gets trapped in a cycle (loop). For example, given the following maze if the starting room is 3 and the end room is 2. The droid will get trapped in a cycle [3, 5, 4, 6, 3]. Your program​ ​should​ ​detect​ ​the​ ​case​ ​where​ ​there​ ​is​ ​no​ ​solution</li>

</ol>


