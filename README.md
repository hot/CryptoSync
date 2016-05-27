# CryptoSync: simple backup you data with more security

##Intro

CryptoSync is a simple,light-weight file backup with AES encryption.
* Sync the whole directory to backup directory,
* AES-256 bit encryption,
* Hash check to skip existed encryped files

##HowTo(Edit the Config.ini)
>Config.ini is a *json* file.

###BackUp:

* Change the mode line to encrypt:
~~~~
"mode" : "encrypt"
~~~~
* fill your password
* edit "encrypt_config" with your source dir and the backup dir
* run csync.py, if you use Windows, double click on csync.py will be fine.

###Restore:

*  Change the mode line to decrypt:
~~~~
"mode" : "decrypt"
~~~~
* fill your password
* edit "decrypt_config" with your source dir and the backup dir
* run csync.py, if you use Windows, double click on csync.py will be fine.

##At Last
>Enjoy yourself;)




