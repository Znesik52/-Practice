# Hangman C++
* This project implements a simple Hangman game in C++ for two players
* One of the players thinks of a word - writes any two letters of the word on paper and marks the places for the remaining letters,
for example, with strokes (there is also an option when initially all the letters of the word are unknown).
A gallows with a noose is also drawn.
* The second player suggests a letter that can be included in this word. If such a letter is in a word, 
then the first player writes it above the lines corresponding to this letter - as many times as it appears in the word.
If there is no such letter, then a circle in a loop representing a head is added to the gallows. 
The second player continues to guess the letters until he guesses the entire word. For each incorrect answer, 
the first player adds one part of the torso to the gallows (usually there are 6 of them: head, torso, 2 arms and 2 legs).