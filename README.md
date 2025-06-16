# Numbering Systems Homework
## Encryption Process
1. Select a secret word
2. Convert the secret word into ASCII
3. Convert the secret word's ASCII into binary
4. Select a word that will act as the key (same length for simplicity)
5. Repeat steps 2-3
6. Apply the XOR bitwise operation between the message and key to get the encrypted message in binary form
7. Convert the encrypted binary message into hexadecimal for easy sharing


 ## Decrypting Process
1. Convert the encrypted hexadecimal message into Binary form
2. Convert key from charcode to binary
3. XOR each binary byte of the encrypted message with the corresponding binary byte of the key.
4. Convert the resulting binary back to decimal ASCII
5. Convert ASCII values to charcodes to reveal the message
(If we have to perform a bitwise XOR when plain text and keys have different lengths, we adjust the key to match the length of the message. If the key is shorter, repeat the key; if the key is longer,
truncate it to match the message length.)

## Challeneges
This exercise was mostly straightforward, as I’ve worked with binary and XOR before. However, the decryption process was the most challenging part for me. I had limited experience reversing the XOR operation and converting between binary, ASCII, and characters. Using the flow chart was especially helpful for visualizing each step of both encryption and decryption. I’ll definitely refer to that resource again in future exercises.

### [Flowchart](images/numberingSystem.jpg)

### Hand-Written Work
[Encryption](images/num1.jpg)
[Decryption](images/num2.jpg)
