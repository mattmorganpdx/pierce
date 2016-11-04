# pierce

# pre-reqs

    - Get the latest version of ansible that has the docker_container mod
        git clone git@github.com:ansible/ansible.git
        cd ansible
        git submodule update --init --recursive
        make
        sudo make install
        
    - Install Docker
        follow these: https://docs.docker.com/engine/installation/linux/ubuntulinux/
        - Run these commands to add your user to the docker group
            sudo gpasswd -a ${USER} docker
	        sudo service docker restart 
	        newgrp docker
	    - Run sudo pip install docker-py
	        If you don't have pip installed google it, that's another story.
	        
	
        
        