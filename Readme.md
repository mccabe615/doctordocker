Use this command to start via Vagrant

vagrant up --provider=docker --no-parallel

You can start individual docker contaniners with the folloing:
vagrant up db --provider=docker
vagrant up web --provider=docker


To ssh into the docker proxy VM:

run vagrant global-status 

vagrant ssh [id of vm]


