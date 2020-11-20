### How to run it

### PRE ansible script

#### Install Pre-reqs
	 $ sudo apt-get install git ansible xmonad -y

#### Clone my repo and run ansible
	 $ git clone https://github.com/nxzthelinuxguy/my-xmonad.git
	 $ cd my-xmonad/
	 $ ansible-playbook -i ansible.cfg setup.yaml      (edit the username in setup.yml before running)

### POST ansible script
After the ansible setup is finished successfully you need to logout or reboot.

#### In the login screen select Xmonad from the bottom right conky wheel 

Once you login, you will see a blank screen with no wallpaper
#### Set wallpaper

#####	Open run prompt
	To open RUN prompt
		MOD + Left Shift + Enter
#####		MOD is the windows key
#####	Search nitrogen 
#####	Open preferences
#####	Select Pictures 
#####	Apply 
