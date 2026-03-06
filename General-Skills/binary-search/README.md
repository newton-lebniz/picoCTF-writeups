# Binary Search

## Category
general skills(easy)

## Description
Want to play a game? As you use more of the shell, you might be interested in how they work! Binary search is a classic algorithm used to quickly find an item in a sorted list. Can you find the flag? You'll have 1000 possibilities and only 10 guesses.
Cyber security often has a huge amount of data to look through - from logs, vulnerability reports, and forensics. Practicing the fundamentals manually might help you in the future when you have to write your own tools!
You can download the challenge files here:
challenge.zip
Additional details will be available after launching your challenge instance.

## Hints
1. Have you ever played hot or cold? Binary search is a bit like that.
2. You have a very limited number of guesses. Try larger jumps between numbers!
3. The program will randomly choose a new number each time you connect. You can always try again, but you should start your binary search over from the beginning - try around 500. Can you think of why?

## Solution
1. so i  connected to the instance ssh -p 52105 ctf-player@atlas.picoctf.net and the guven password
2. then as stated in the hint i started with 500
3. each time itll say if u have to go highed=r or lower
4. and i used the half strategy like this is how i got the flag 
Welcome to the Binary Search Game!
I'm thinking of a number between 1 and 1000.
Enter your guess: 500
Lower! Try again.
Enter your guess: 250
Lower! Try again.
Enter your guess: 125
Lower! Try again.
Enter your guess: 63
Lower! Try again.
Enter your guess: 31
Congratulations! You guessed the correct number: 31

## Flag
picoCTF{g00d_gu355_3af33d18}