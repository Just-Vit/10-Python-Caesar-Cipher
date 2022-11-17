# python-caesar

>>>> Caesar Cipher with Python

Create working directory

└─$ mkdir pyCaesar

└─$ cd pyCaesar


To run Caesar encryption with Python please follow these steps:

(Caesar encryption is based on adding a given step to each letter in the message,
for example, a message "aaa" with a stride of "1" would create an encrypted message "bbb").

As a prerequisite, you must have Python installed on your system.
And in the case of a remote server, this is not the easiest task.

Either way, make a copy of the URL from 'Code' > 'Clone' > 'HTTPS' and set to your working directory.

└─$ git clone https://github.com/vi-u/Python-Caesar.git

└─$ ls

Python-Caesar

└─$ cd Python-Caesar

To run it from your working directory, just type the command:

└─$ python cc_encrypt.py

As a result, you should get something like this:

└─$ python cc_encrypt.py
Welcome to Caesar Cipher Encryption.

Enter the message you want to encrypt: AaZz

Enter cipher step: 1

Encrypting your message...

Wait, almost done...

Your encrypted message:

bbaa


*** 
Same command goes with decryption

└─$ python cc_dencrypt.py 
