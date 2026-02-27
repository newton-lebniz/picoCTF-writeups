# HASHCRACK

## Category
cryptography

## Challenge Description
A company stored a secret message on a server which got breached due to the admin using weakly hashed passwords. Can you gain access to the secret stored within the server?
Additional details will be available after launching your challenge instance.

## Hints
1. Understanding hashes is very crucial. Read more here(https://primer.picoctf.org/#_hashing)
2. Can you identify the hash algorithm? Look carefully at the length and structure of each hash identified.
3. Tried using any hash cracking tools?

## Solution
1. launch the instance and connect to  nc verbal-sleep.picoctf.net 56457
2. got a hash there 482c811da5d5b4bc6d497ffa98491e38
3. decoded it on an online tool and got password123
4. got another hash b7a875fc1ea228b9061041b7cec4bd3c52ab3ce3
5. decoded it and got letmein
6. got another hash 916e8c4f79b25028c9e467f1eb8eee6d6bbdff965f9928310ad30a8d88697745
7. decode it and got it qwerty098
8. got the flag

## Flag
picoCTF{UseStr0nG_h@shEs_&PaSswDs!_4de57566}