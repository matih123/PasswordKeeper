# mysqlvault
Available on android and windows.

## Download .apk, .exe from https://mysqlvault.tk

## General information
App made in kivy for managing passwords stored on mysql database.

In the database passwords are encrypted using PBKDF2 with salt.
App decrypts them using provided key after they are downloaded.

You can create your own database with all needed tables using database.py python script.

After successful login database address, port and username are automatically saved to config file. 
Instead of typing these details every time you can simply click on USE DEFAULT. It will load last used login data.

## Overview
![app overview image](img/overview.png?raw=true "Title")

