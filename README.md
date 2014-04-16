encrypted-text-editor
=====================

Qt/Crypto++ encrypted text editor example

Takes the MDI (Multiple Document Interface) text editor Qt5.2 example and tacks on usage of Crypto++ 5.6 for SHA256 hashing of password and AES256 for encryption/decryption of HTML backed rich text editor.  Text editor prompts for password when opening and closing.  This project is otherwise very bare bones and lacks rich editing or any forms of obfuscating the AES256 key in memory.

Builds
=======

Mac
---
v0.1: https://s3.amazonaws.com/captemulation/dmg/Encrypted_Text_Editor.dmg


Building you self
========
You will need to build Crypto++ yourself.  I used Crypto++ 5.6.2.  Adjust the CRYPTOPP_LIB variable in encrypted-text-editor for your environment

License
=======
See LICENSE
