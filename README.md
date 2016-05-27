# CryptoSync: simple back you data more security

##Intro

CryptoSync is a simple,light-weight file backup with AES encryption.
* Sync the whole directory to backup directory,
* AES-256 bit encryption,
* Hash check to skip existed encryped files

##HowTo
>Config.ini is a *json* file.

###BackUp:

####Change the mode line to encrypt:
~~~~
"mode" : "encrypt"
~~~~

* Restore:
 *  Change the mode line to decrypt:
  * "mode" : "decrypt"


Edit the config.ini and just Run 
>python csync.py




