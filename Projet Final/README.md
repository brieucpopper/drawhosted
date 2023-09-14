(this read me file is a work in progress)


# Visual Demo : running 4 players on one screen

<video src='https://github.com/brieucpopper/drawhosted/blob/master/Projet%20Final/video-1646009527.mp4' width=180/>

# Quick presentation

This game is a two vs two drawing game. Each team receives a word (say "door") and has to draw a door, but there's a catch ! Both player draw on the same canvas, and each can only draw on half the canvas.<br>
This way each player participates in a drawing. At the end of the round, the teams are mixed up and another word comes up. At the end of a given number of round, the game ends and players get to vote for each drawing (if they like it more or less)<br>
Then the best drawings give players who elaborated them more points and the winner is chosen !

<br><br>
Technically working on this project was interesting as I learned about hosting a web server on a linux server, learned to code an interactive Javascript web application with sockets, and finally a simple python flask server to interact with sockets and implement this game, with multiple separate "rooms" if multiple players want to play in parallel.
![tkt](https://user-images.githubusercontent.com/102361078/216851081-d4d83753-2b66-4ecc-a6ba-a0930ecbe00b.png)


# INSTRUCTIONS


Le plus simple pour jouer est de se rendre sur http://draw2io.h.minet.net (is currently in maintenance)



sur ce site il suffit alors de jouer au jeu, en suivant les règles qui sont rappelées sur le site


rapidement les étapes Sont
1. choix de la salle dans laquelle jouer parmi les 10 (il faut se retrouver a 4 dans une meme salle pour jouer)
2. choix du nom, entrer en file d'attente, attendre que 4 joueurs soit en file d'attente
3. phase de dessins, utiliser le clic gauche de sa souris et la déplacer pour dessiner, suivre le thème, dessiner sur sa moitié d'écran dans la limite de temps imparti
4. phase de votes, voter pour les dessins en leur attribuant une note
5. fin


# HOSTER SOI MEME UN SERVEUR

Sur le site web on se connecte à un serveur qui fait tourner 10 serveurs python flask qui sont les 10 "salles"

On peut soi-meme créer une salle en lancant avec la commande "python3 app.py i" un serveur qui sera sur le port 5000+i

Puis s'y connecter en localhost (lancer index.html en local)


<h1> ENGLISH VERSION </h1>

This is a 2v2 drawing game similar to a build battle from minecraft (each player has to draw something related to a keyword with a partner but can only use a part of the screen, then votes for his favorite drawings)
instructions to play are given on the website
