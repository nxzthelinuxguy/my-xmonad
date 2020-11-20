### How to run it

#### Install Pre-reqs
	 $ sudo apt-get install git ansible xmonad -y

#### Clone my repo and run ansible
	 $ git clone https://github.com/nxzthelinuxguy/my-xmonad.git
	 $ cd my-xmonad/
	 $ ansible-playbook -i ansible.cfg setup.yaml      (edit the username in setup.yml before running)
