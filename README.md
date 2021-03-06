# CTF-toolkit

## Tools to use in cybersecurity ctf challenges

### BASIC OPERATIONS


Change directory: 
```cd directory``` EX: ```cd Desktop```

Grep for a string throughout all the files in a directory:
```grep -rni "string"```

Open javascript node in linux shell:
```Node```

Show all files (including hidden ones) in a directory: ```ls -a```

Connect through netcat:
``` nc *server address* *port* ``` EX: ```nc thisisaurl.url 123456```

Run a python program
```python filename.py```
```diff
- MAKE SURE YOU HAVE PYTHON INSTALLED
```

Run a program (executable/bin)
```./filename```
```diff
- MUST BE IN DIRECTORY OF PROGRAM
```


### FORENSICS AND CRYPTOGRAPHY TOOLS

[Forensically](https://29a.ch/photo-forensics/#forensic-magnifier)

Great for images with metadata, escaped strings or hidden messages

[Stenography Tool](https://stylesuxx.github.io/steganography/)

Also great for decoding images, contains some features that Forensically doesn't

### DECRYPTERS

[ROT13 Cryptii](https://cryptii.com/pipes/rot13-decoder)

Encodes and decodes using the ROT13 substitution cipher

[Caesar Cipher Cryptii](https://cryptii.com/pipes/caesar-cipher)

Encodes and decodes using a caesar cipher (you get to pick the key)

[Maritime Signals dCode](https://www.dcode.fr/maritime-signals-code)

Encodes and decodes using a maritime signal cipher. Site has gui keyboard to manually enter signal characters.

[Alphabetic Substitution Cipher dCode](https://www.dcode.fr/monoalphabetic-substitution)

Encodes and decodes using a monoalphabetic substitution cipher. Site has a gui editor to manually enter keywords or predict character assignments.

[RSA Encryption Wiki](https://simple.wikipedia.org/wiki/RSA_algorithm)

Wikipedia page explaining the RSA encryption algorithm.

[Encoding Tools](https://encoding.tools/)

A handy graphical utility that contains encoders/decoders for multiple uncommon encryption techniques such as URL and Base64.

```diff
+ NOTE: CRYPTII HAS ENCRYPTION/DECRYPTION SITES FOR MANY DIFFERENT FORMS OF ENCRYPTION (HEX, OCT, ASCII, ETC)
```
### WEB EXPLOITATION TOOLS

[SQLi (SQL injection) Cheat Sheet](https://www.netsparker.com/blog/web-security/sql-injection-cheat-sheet/)

This cheat sheets (not all-inclusive) contains many common SQL injection queries to use.

SQL injection truth statement: ```' OR '1'='1' --```

[Flask injection cheat sheet](https://pequalsnp-team.github.io/cheatsheet/flask-jinja2-ssti)

If the website uses flask.

Change the browser the website thinks you're using: ```curl --user-agent "newbrowser" "https://thisisaurl.url"```

[Javascript Deobfuscator](https://lelinhtinh.github.io/de4js/)

Deobfuscate your javascript...

IMPORTANT FILE: ```robots.txt``` may be in the website to hide information from robots.

### PROGRAMMING TOOLS

[PWN Tools](http://docs.pwntools.com/en/stable/)

This python library includes CTF specific functions such as stack overflow tools (dealing with little-endian and big-endian bytes), flag detection tools, and simple socket connection (send and recieve) tools. This library helps cut down the amount of time it takes to develop a python program to solve various different CTF challenges.



