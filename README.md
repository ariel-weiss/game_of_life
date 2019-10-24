# game_of_life
<h3>Game of Life, programmed in multi-threaded way (course assignment).</h3>

<br>
<h4>
How to run:
</h4>
Use the makefile('make' command) and use the input parameters:
<br>
(1) text file path
<br>
(2) number of cycles
<br>
(3) number of threads
<br>
(4) animation output (Y-yes,N-no)
<br>
(5) display output (Y-yes,N-no)
<br>
<h5>
example:
</h5>
The command:<br><code>
./GameOfLife mid.txt 10 4 Y Y </code><br>
Will use mid.txt as starting board, run for 10 cycles using 4 threads and display output as animation. 
<h5>
The files I implemented:
</h5>
-Game.cpp<br>
-Game.hpp<br>
-PCQueue.hpp<br>
-Semaphore.cpp<br>
-Thread.hpp<br>
<br>
