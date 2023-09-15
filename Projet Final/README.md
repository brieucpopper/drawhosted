(this read me file is a work in progress)


# Visual Demo : running 4 players on one screen

[Link to youtube video demo](https://www.youtube.com/watch?v=Jdf3ohmjG1M)

In the demo the player are not really drawing any given "word", it's just a proof of concept. An actual game would have way more times for players to draw each round, and a variety of different things to draw (a cat, a house...)


# Quick presentation

This game is a two vs two drawing game. Each team receives a word (say "house") and has to draw a house, but there's a catch ! Both player draw on the same canvas, and each can only draw on half the canvas.<br>
This way each player participates in a drawing, but only by drawing on half the possible canvas. This means that your cooperation skills are crucial to get to a good final result! At the end of the round, the teams are mixed up and another word comes up. At the end of a given number of round, the game ends and players get to vote for each drawing (if they like it more or less)<br>
Then the each player gets more or less points depending on whether the drawings he had a part in had good votes or not, and the final winner is chosen !

<br><br>
Technically working on this project was interesting as I learned about hosting a web server on a linux server, learned to code an interactive Javascript web application with sockets, and finally a simple python flask server to interact with sockets and implement this game, with multiple separate "rooms" if multiple players want to play in parallel.
![tkt](https://user-images.githubusercontent.com/102361078/216851081-d4d83753-2b66-4ecc-a6ba-a0930ecbe00b.png)

