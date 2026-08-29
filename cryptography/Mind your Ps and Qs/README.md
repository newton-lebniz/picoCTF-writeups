# Mind your Ps and Qs

## Category
cryptography(Medium)

## Challenge description
In RSA, a small e value can be problematic, but what about N? Can you decrypt this?

## Hints
1. Bits are expensive, I used only a little bit over 100 to save money

## Solution
1.  opened the file and got the rsa values
Decrypt my super sick RSA:
c: 15341890103764929939105506004034128738090325640037083301857608662849501626260517
n: 948406957756830799684818171639547165784816468744946013083947881743680617123566349
e: 65537
2. used a RSA decoder and got the flag but its backwards - ( }19ea7cd1_do0g_0n_N_11ams{FTCocip )

## Flag
picoCTF{sma11_N_n0_g0od_1dc7ae91}