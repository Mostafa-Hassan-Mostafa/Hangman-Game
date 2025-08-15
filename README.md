<!-- Animated Header -->
<h1 align="center">🎯 Hangman Game - Country Guess</h1>
<h3 align="center">Classic Word Guessing Game with ASCII Art</h3>

<!-- Typing Animation -->
<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?size=20&duration=3000&color=2196F3&center=true&vCenter=true&width=600&lines=Word+Guessing;ASCII+Art+Display;Multiple+Wrong+Guesses+Allowed" alt="Typing Animation" />
</p>

---

## 📖 Project Overview
A console-based **Hangman game** implemented in Python.  
The player must guess the name of a country from a predefined list of **Arab countries**.  
The game displays an ASCII art hangman that updates with each wrong guess.

> 📌 This project improves **logic building**, **loops**, **conditionals**, and **string manipulation** skills.

---

## 🛠 Tools & Skills Used
<p align="center">
<img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
<img src="https://img.shields.io/badge/ASCII%20Art-000000?style=for-the-badge&logo=ascii&logoColor=white"/>
<img src="https://img.shields.io/badge/Game%20Logic-FF5722?style=for-the-badge&logo=joystick&logoColor=white"/>
</p>

---

## ✨ Features
- Randomly selects a country from a list.
- Player guesses letters one by one.
- Keeps track of guessed letters.
- Displays ASCII hangman art for wrong guesses.
- Ends game when:
  - The player guesses the word.
  - The player runs out of guesses.

---

## 🖥 Example Usage


*************
_ _ _ _
Enter a letter: o
*************
  O  
     
     
*************
_ _ _ _
Enter a letter: m
*************
  O  
  |  
     
*************
_ _ _ _
Enter a letter: i
*************
  O  
  |  
     
*************
i _ _ _
Enter a letter: w
*************
  O  
 /|  
     
*************
i _ _ _
Enter a letter: r
*************
  O  
 /|  
     
*************
i r _ _
Enter a letter: o
o is already guessed
*************
  O  
 /|  
     
*************
i r _ _
Enter a letter: p
*************
  O  
 /|\
     
*************
i r _ _
Enter a letter: a
*************
  O  
 /|\
     
*************
i r a _
Enter a letter: m
m is already guessed
*************
  O  
 /|\
*************
i r a _
Enter a letter: q
*************
  O  
 /|\
*************
i r a q

YOU WIN!
