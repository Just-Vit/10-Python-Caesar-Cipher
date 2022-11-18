# Python-Caesar-Cipher

>>>> Caesar Cipher with Python

To run Caesar encryption with Python, follow these steps:

(Caesar encryption is based on adding a given stride (integer) to each letter in the message.
For example, a message "aaa" with a stride of "1" would create an encrypted message "bbb").

As a prerequisite, you must have Python installed on your system.
And in the case of a remote server, this is not an easy task.

Either way, make a copy of the URL from 'Code' > 'Clone' > 'HTTPS' and set it to your working directory.

    $ git clone https://github.com/vi-u/10-Python-Caesar-Cipher.git

    $ ls

└─  10-Python-Caesar-Cipher

    $ cd 10-Python-Caesar-Cipher

To run it from your working directory, just type the command:

    $ python cc_encrypt.py

As a result, you should get something like this:

└─$ python cc_encrypt.py

└─ Welcome to Caesar Cipher Encryption.

└─ Enter the message you want to encrypt: AaZz

└─ Enter cipher step: 1

└─ Encrypting your message...

└─ Wait, almost done...

└─ Your encrypted message:

└─ bbaa


*** 
A similar command performs decryption

    $ python cc_dencrypt.py 
