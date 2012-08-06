# New Machine

New Machine is a script to setup a Mac OS X machine for Rails Development.

# Requirements
----------------------------------
1. Xcode 4.4
2. Install the Command Line Tools for Xcode. (Xcode > Preferences > Downloads > Command Line Tools)
3. zsh - oh-my-zsh or 
	chsh -s /bin/zsh

Run this script:
```
	zsh < <(curl -s https://raw.github.com/seriousfox/new-machine/master/setup)
```	
	
# Word Jumping in iTerm
---------------------------------
How to set up Word jumping:

In Preferences, add shortcut keys thus:

- shortcut keys: option ← and → - action: send escape sequence - in the escape sequence box enter 'b' and 'f' respectively

# This Script Installs the following:
--------------------------------------------
- mongo
- redis
- ImageMagick
- MySQL
- Postgres
- Redis
- MongoDB
- QT


## Credits

This is very much based upon https://github.com/thoughtbot/laptop