# Flag in Flame

## Category
Forensics(easy)

## Challenge Description
The SOC team discovered a suspiciously large log file after a recent breach. When they opened it, they found an enormous block of encoded text instead of typical logs. Could there be something hidden within? Your mission is to inspect the resulting file and reveal the real purpose of it. The team is relying on your skills to uncover any concealed information within this unusual log.
Download the encoded data here: Logs Data. Be prepared—the file is large, and examining it thoroughly is crucial .

## Hints
1. Use base64 to decode the data and generate the image file.

## Solution
1. so as per the hint i base64 decoded the file into an image file
2. when i opened the image i found a string in it
3. i pasted the string on my decoder(i have it in github too)
4. it gave me the flag

## Flag
picoCTF{forensics_analysis_is_amazing_5ccc7cb0}