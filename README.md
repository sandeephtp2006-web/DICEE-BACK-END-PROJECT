# DICEE-BACK-END-PROJECT
"A simple two-player Dicee game built using HTML, CSS, and JavaScript. Each page refresh rolls two dice and displays the winner based on random numbers. Lightweight, beginner-friendly, and perfect for learning basic DOM manipulation and interactivity."
🎲 Dicee Game

A simple and fun two-player dice game built using HTML, CSS, and JavaScript.
Every time you refresh the page, the dice roll randomly and the game declares a winner.

 Features

 Random dice roll for both players

 Automatically displays the winner

 Simple and beginner-friendly code

 Uses Google Fonts (Indie Flower & Lobster)

 Project Structure
Dicee/
│
├── index.html
├── styles.css
├── index.js
└── images/
      ├── dice1.png
      ├── dice2.png
      ├── dice3.png
      ├── dice4.png
      ├── dice5.png
      └── dice6.png

 How It Works
HTML

Creates the layout

Two players

Each player gets one dice image

JavaScript changes these dice images on refresh

CSS

Styles the page

Centers dice

Adds custom fonts

JavaScript (index.js)

Generates two random numbers (1–6)

Changes dice images using:

document.querySelector(".img1").setAttribute("src", "images/dice" + randomNumber1 + ".png");


Compares both dice

Updates the <h1> heading with the winner

 How to Run

Download or clone the repository

git clone https://github.com/your-username/dicee-game.git


Open index.html in your browser

Refresh the page to roll the dice 🎲

