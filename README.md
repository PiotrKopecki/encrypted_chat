# Encrypted-chat

## The main goal of the project is to realize a software tool for sending files and messages in unsecure environment. Before the transmission process, the session key must be generated and securely transmitted to the other user.

### ConfigFile.py is required to run this app, schema how it should look like is in ConfigFileTemp.py
### RUN whole application:
  ``` docker compose up --build ```
  
### Demo:
#### If you dont know what ip you should provide while connecting as client, go ahead and check out console log after performing third step on host side

https://github.com/Michaqu11/encrypted-chat/assets/78599029/8862f18a-c6e4-47f2-966c-2dd18b32f36f

### Tech stack:
  - Typescript / Vue
  - Python / Django
  - Firebase

### Used encrytpion methods:
  - RSA
  - AES (EBC, CBC)
  - SHA

### Used libraries:
  - Socket
  - WebSocket
  - bcrypt
  - pyrebase
  - cryptography
  - base64
  - hashlib
  - file-saver (vue)



