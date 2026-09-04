# 2v2 Drawing Competition Web Game
*Started Apr 2022 — web programming project @ Telecom SudParis*

[Video demo (4 players on one screen)](https://www.youtube.com/watch?v=Jdf3ohmjG1M)

Two teams of two get the same word (e.g. "house") and have to draw it — except both players share one canvas and each can only draw on half of it. Cooperation matters. After a few rounds with shuffled teams, players vote on drawings and a winner is picked.

The demo above is a proof of concept (no real words, short rounds). A full game would have longer rounds and varied prompts.

## How it works

- Interactive canvas app in JavaScript (p5.js) with sockets
- Python Flask server, hosted on a Linux server, with multiple parallel "rooms"
- See `client/` and `server/`, plus `Livrables écrits/` (in French) for the full report

![game](https://user-images.githubusercontent.com/102361078/216851081-d4d83753-2b66-4ecc-a6ba-a0930ecbe00b.png)
