### HOW TO RUN IT
### PRE ansible script

#### Install Pre-reqs
	 $ sudo apt-get install git ansible xmonad -y

#### Clone my repo and run ansible
	 $ git clone https://github.com/nxzthelinuxguy/my-xmonad.git
	 $ cd my-xmonad/
	 $ ansible-playbook -i ansible.cfg setup.yaml      (edit the username in setup.yml before running)

### POST ansible script
	Take a clean reboot.

#### In the login screen 
	select Xmonad in the bottom right wheel  
Once you login, you will see a blank/black screen with no wallpaper

#### Set a wallpaper

##### Open RUN PROMPT
#####	MOD is the WINDOWS KEY
		- MOD + Shift + Enter
			- Search nitrogen 
			- Open preferences
			- Select Pictures 
			- Apply

##### Next setup mouse pointer
	Open prompt:
		- MOD + Shift + Enter
		- Search for lxappearance
		- Select desired theme
		- Select desired cursor
		- Apply

### My config file is a bit bloated with lots of settings, modify it according to your need
### You may have to change 
	- Tree select
	- Grid select 
	- And bindings according to your need 
### Most of the bindings will work for you !

### NOTE For Key bindings refer your xmonad config file
#### It is located at your home directory
	$ ls ~/.xmonad/xmonad.hs 

##### Open and search for myKey
##### Below myKey you will find all the bindings
##### Refer and change or delete according to your needs

### Here are some basic key bindings
#####	MOD is the WINDOWS KEY
#####	MOD1 is the ALT KEY
###### Basic Bindings
	MOD + Enter		==>	Opens terminal
	MOD + b			==>	Opens firefox browser
	MOD + Shift + c		==>	Close currently selected window
	MOD + Shift + a		==>	Close all windows
###### Xmonad Bindings
	MOD + q			==>	Restart Xmonad  (useful when xmonad.hs is modified)
	MOD + Shift + q		==>	Logout
	MOD + Shift + r		==> 	Recompile Xmonad
###### PROMPT Bindings (MOD + p is a prefix, press and leave the key DONT HOLD)
	MOD + Shift + Enter	==>	Opens Run prompt
	MOD + p + s		==>	SSH prompt
	MOD + p + m		==>	Manual Page prompt 
	MOD + p + x		==>	Xmonad prompt 
	MOD + p + p		==>	get password (requires pass)
	MOD + p + g		==>	generate password (requires pass)
	MOD + p + r		==>	remove password (requires pass)

###### SEARCH PROMPT
	MOD + s + a		==>	Search arch wiki prompt
	MOD + s + e		==>	Search ebay prompt 
	MOD + s + g		==>	Search google prompt 
	MOD + s + h		==>	Search hoogle prompt
	MOD + s + i		==>	Search google images prompt 
	MOD + s + n		==>	Search news prompt
	MOD + s + r		==>	Search reddit prompt 
	MOD + s + s		==>	Search stackage prompt 
	MOD + s + t		==>	Search thesaurus prompt 
	MOD + s + v		==>	Search vocabulary prompt 
	MOD + s + w		==>	Search wikipedia prompt
	MOD + s + y		==>	Search youtube prompt


###### TREE SELECT Bindings (CTRL + t is a prefix, press and leave the key DONT HOLD)
	CTRL + t + t		==>	My Tree view
###### GRID SELECT Bindings (CTRL + g is a prefix, press and leave the key DONT HOLD)	
	CTRL + g + g		==>	My Grid view
	CTRL + g + t		==>	Tab view of open windows
	CTRL + g + b		==>	Bring selected view to current workspace

