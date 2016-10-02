Ansible Examples 

After base OS .. shell provisioning within the Vagrant file , we used epel-release repository added as a part of shell provisioning within the vagrant , so that once the vagrant brought up the machine , it will execute anything under the shell tag. 

After the initial Vagrant up command , if we modify the vagrant file, then we need to use --provision flag .

EX:- vagrant up --provision , else we get error that the vagrant already provisioned the perticular environment .
