Nim.java

The Nim.java main communicates directly with the Game.java class through line 7 of Nim.java.
Game.java communicates with Human.java and Computer.java through line 14 and 15 of Nim.java. 
Human.java and Computer.java are self-contained and don’t rely on other classes. In Game.java 
I set the random difficulty settings to balanced, to give an equal chance for each setting in 
either smart or stupid mode before prompting the user to make a selection. In the method in 
Game.java I utilized a significant while loop to count the marbles left, indicating the computer 
or human player selection total, and ultimately declaring a winner. The Human.java move method 
includes if and else statements with a while loop to prompt the human player for a selection 
and advise on whether that selection is within the guidelines stipulated in the problem set. 
The Computer.java move method includes a boolean to indicate the number of marbles 1 less than 
a power of 2, between 0 and 100 per the instructions. The mode selected and the special numbers 
determine the computer’s ability to win the game. I used an else if loop in this section for 
algorithm efficiency. 
