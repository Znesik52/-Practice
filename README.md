# Hangman C++
* This project implements a simple Hangman game in C++ for two players
* Один из игроков загадывает слово — пишет на бумаге любые две буквы слова и отмечает места для остальных букв,
например чертами (существует также вариант, когда изначально все буквы слова неизвестны).
Также рисуется виселица с петлёй.
* The second player suggests a letter that can be included in this word. If such a letter is in a word, 
then the first player writes it above the lines corresponding to this letter - as many times as it appears in the word.
If there is no such letter, then a circle in a loop representing a head is added to the gallows. 
The second player continues to guess the letters until he guesses the entire word. For each incorrect answer, 
the first player adds one part of the torso to the gallows (usually there are 6 of them: head, torso, 2 arms and 2 legs).