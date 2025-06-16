# Numbering Systems Homework
## Encryption Process
1. Select a secret word
2. Convert the secret word into ASCII
3. Convert secret word ASCII into binary
4. Select a word that will act the key (same length for simplicity)
5. Repeat steps 2-3
6. Apply XOR bitwise operation between the message and key to get encrypted message in binary form
7. Convert encrypted binary message into hexadecimal for easy sharing


 ## Decrypting Process
1. Convert encrypted hexadecimal message into Binary form
2. Convert key from charcode to binary
3. XOR each binary byte of encrypted message with corresponding binary byte of key.
4. Convert resulting binary back to decimal ASCII
5. Convert ASCII values to charcodes to reveal message

### LINK TO FLOWCHART
