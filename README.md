# Hangman Game - Arab Countries Edition

🎯 A Python implementation of the classic **Hangman** game where the player guesses letters to find the name of an Arab country. The game displays ASCII art for each stage of the hangman as wrong guesses are made.

---

## Features
- Predefined list of **Arab country names** as words to guess.
- ASCII art hangman that updates with each wrong guess.
- Input validation to ensure only single letters are entered.
- Prevents duplicate guesses by tracking already guessed letters.
- Win or lose messages with the correct answer displayed.

---
Example:

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
Enter a letter: v
*************
  O  
 /|\
 /   
*************
i r a _
Enter a letter: q
*************
  O  
 /|\
 /   
*************
i r a q

YOU WIN!
