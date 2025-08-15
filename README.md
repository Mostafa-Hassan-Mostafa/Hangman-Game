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
     
     
     
*************
_ _ _ _ _

Enter a letter: e
*************
     
  |  
     
*************
e _ _ _ _

Enter a letter: g
*************
  O  
  |  
     
*************
e g _ _ _

Enter a letter: y
*************
  O  
 /|  
     
*************
e g y _ _

Enter a letter: p
*************
  O  
 /|\ 
     
*************
e g y p _

Enter a letter: t
*************
  O  
 /|\ 
     
*************
e g y p t
YOU WIN!
