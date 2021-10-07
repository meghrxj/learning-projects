# Battleship Style Game: "Sink a Dot Com"

<strong>Goal: </strong>Sink all of the computer's Dot Coms in fewest number of guesses

<strong>Setup: </strong>When the game program is launched, the computer places three Dot Coms on a virtual 7x7 grid. When that's complete the gae asks for your first guess. 

<strong>How you play: </strong>Computer will prompt you to enter a guess(cell), that you'll type at the command-line as "A3", "C5", etc. In response to your guess, you'll see a result at the command-line, either "Hit", "Miss", Or "you sank xyz.com"
When you've sent all three Dot coms to that big 404 in the sky the game ends by printing you rating. 

//General Flow of the game
1.<strong> User Starts the game</strong>
<strong>A </strong>Game creates three Dot Coms
<strong>B </strong>Game places the three Dot Coms onto a virtual grid

2.<strong> Game play begins</strong>
Repeat the following until there are no more Dot Coms:
<strong>A </strong>Prompt user for a guess
<strong>B </strong>Check the user guess against all Dot Coms to look for a hit, miss, or kill. Take appropriate action: if a hit, delete cell. If a kill, delete Dot Com.

3.<strong> Game Finishes</strong>
Give the user a rating based on the number of guesses

<a href="https://ibb.co/r5JVjtr"><img src="https://i.ibb.co/GCjq6JS/image-2021-10-07-232554.png" alt="image-2021-10-07-232554" border="0"></a>


## Resource 
<a href="https://www.oreilly.com/library/view/head-first-java/0596009208/">Head First - Java</a>