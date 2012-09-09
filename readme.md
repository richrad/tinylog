#Tinylog

A command-line utility for keeping a private diary.

#Requirements

* tree
* aescrypt
	
#Usage

    tinylog init

Creates the directory for your entries to be stored in.

    tinylog
	
Displays the directory structure of your entries.

    tinylog new
   
Creates a new entry.

    tinylog open YEAR/MONTH/FILE
	
Opens the specified entry.

    tinylog lock
	
Encrypts the contents of your tinylog directory. You'll be prompted to create a password.

    tinylog unlock
	
Decrypts your tinylog.

#Customize

You can change the default text editor and file path in tinysettings.cfg.

#Copying

Go crazy!