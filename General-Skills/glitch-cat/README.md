# Glitch Cat

## Category
General Skills(Easy)

## Challenge Description
Our flag printing service has started glitching!
Additional details will be available after launching your challenge instance.

## Hints
1. ASCII is one of the most common encodings used in programming
2. We know that the glitch output is valid Python, somehow!
3. Press Ctrl and c on your keyboard to close your connection and return to the command prompt.

## Solution 
1. After launching the instance you'll find $ nc saturn.picoctf.net 57987
2. Connect to it
3. There i found 'picoCTF{gl17ch_m3_n07_' + chr(0x62) + chr(0x64) + chr(0x61) + chr(0x36) + chr(0x38) + chr(0x66) + chr(0x37) + chr(0x35) + '}'
4. As stated in the hint 2 it is a python code
5. So i ran it in python3 and got the answer..

## Flag
picoCTF{gl17ch_m3_n07_bda68f75}