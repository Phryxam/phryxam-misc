# Problem 1
## Et tu, Brute? (5 points):
```
I found a message from Julius. Can you get the flag?
Huk aopz pz aol mshn: clup_cpkp_cpjp_TqT1TK
```
Based on the title of the problem and the message, we can assume that this is a Caesar Cipher.
To solve a Caesar Cipher, we need to figure out how far each letter is from the encrypted message.
To begin with, we pick a word in the encrypted message and figure out a word that can be made from
our encrypted message by adding different numbers. I picked AOPZ and did this to try and find a key to test:
```
DIGIT1:00000000001111111111222222
DIGIT2:01234567890123456789012345
       ABCDEFGHIJKLMNOPQRSTUVWXYZ
       OPQRSTUVWXYZABCDEFGHIJKLMN
       PQRSTUVWXYZABCDEFGHIJKLMNO
       ZABCDEFGHIJKLMNOPQRSTUVWXY
                          ^
```
With a key of 19, you can find the word: THIS

With a key of 19, the entire message turns into:
    And this is the flag: veni_vidi_vici_MjM1MD

So therefore our flag is `veni_vidi_vici_MjM1MD`
