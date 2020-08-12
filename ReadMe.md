MegaCheckers:
![image](https://user-images.githubusercontent.com/64987634/89836775-15902180-db2d-11ea-80cd-c39d432bcc4d.png)
First off, special thanks to anyone reading this, and especially a huge thank you to PySimpleGUI and the creator, Mike, for making an accessible GUI framework that anyone can use.  Without it, this game would not have been possible.  

This game is my first foray into making a full game solo that can be enjoyed for hours at a time.  While I have made a few other games,they have generally been kind of short and repetitive, or not visually appealing.  Back in college in like 2014 during my lunch breaks, I used to play a very interesting game named QuadRadius.  Unfortunately, it was a very obscure game and it was hard to find opponents.  I remember thinking "I'd love to make a game like this some day", but didn't have any GUI skills at the time - not to mention there was notime to consider making a game like that when I was doing 12-14 hour courseloads followed by working full time. 

After graduating from that university and then moving on to getting another degree at another university, I finally found some time to trymy hand at recreating the game.  I was disappointed to see the Quadradius game's servers had gone offline, the only remaining traces being forum posts by people complaining that no one was playing anymore and that the servers were down for long periods at a time. So I decided this was my chance to follow through with my goal of recreating the game - but also putting my own touch on it.  I studied up on GUIs and PySimpleGUI and Python ended up being the perfect marriage of tools for creating this game.  I hit the ground running, metaphorically of course, and wrote a quick MineSweeper clone first (you can actually find that exact game on my GitHub as PySweeper), and once I was content that I understood how to create a grid and display it, I went ahead and begun working on my new game - MegaCheckers.

MegaCheckers is a game where you and an opponent take turns moving your respective pieces.  The goal is to make it to where your opponent has 0 pieces under his/her control.  The moment a player has no pieces, they immediately lose.  In order to reach this goal, you move your own pieces in one of four cardinal directions.  The intermediate goal is to kill enemy pieces by jumping on top of them.  Doing this crushes the piece and removes it from the game forever.  However, that's essentially just checkers (with slightly different movement directions).  Nay, what we are discussing is MEGA checkers.  What sets us apart from regular checkers?  Why, items of course!

This game (at the time of version 1.0) has 85 items that can do almost anything you can conceive of - usually with a range dealing with rows/columns/radials (the immediate surrounding grid 3x3 grid).  Want to set a row on fire?  I've got that!  The napalm row is the piece of choice.  Want to shield your pieces from enemy items?  The Energy Forcefield is your ticket.  Wanna steal your enemy's pieces?  I've got an item for that!  Wanna let your pieces go on a rampage and keep destroying multiple enemies in quick succession?  There's a berzerker item for that.  Wanna abuse the laws of time and space?  I have a "recall" item  that'll teleport your piece back in time, and a "round earth theory" that allows you to abuse the boundaries of the field as though they never existed!   Bored of moving straight?  There's a diagonal movement upgrade!  There's teleporters!  There's even an item that'll cause an earthquake that can change the elevation of the playing field - adding (literally) another dimension of challenge to the game!  Thanks to this huge number of items, every round you play will be completely different.  The items are spawned completely at random, so although skill will be very useful since you have to strategize how you will play your items, the completely random luck factor for where items spawn and which ones spawn (and when they spawn) means anyone can hop into the game and win against long time players if they let their guard down (or if they just have absolutely terrible luck... but hey, the games are designed to be very short, so even if you lose, you can have your revenge in minutes)!

I hope you enjoy this game, as I have put in many, many, many hours into it (feel free to check my commits to see the progress I've made on this game since the beginning - the changeLog is also an excellent look into how the game has progressed over the weeks).  I am also always open to bug reports, suggestions (this very readme was made on the suggestion of a couple of people I met on online forums that gave the game a shot) and compliments/criticisms/job offers (heh).  Looking forward to hearing feedback, and thanks for reading this/playing my game.  

