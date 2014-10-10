# README #

This is a template Ansible playbook structure.
It is designed to be the base for new Ansible Playbook projects setting out a folder structure alon ght e Ansible best practices guidelines.
Any suggestions for improvements to this use the issue queue or tweet me @ibluebag

## Usage

Download this (as opposed to cloning it) to form the base of a new project.
Edit as required and update the readme specific to your project.
A sample base role is provided that you can use.
To create new roles use the following command in terminla within the roles directory.
````
ansible-galaxy init 'newrolename'
````
and that will create a role folder structure for you to use.

Ansible best practices can be read about here: http://docs.ansible.com/playbooks_best_practices.html

I strongly recommend purchasing a copy of the Ansible for Devops book by Jeff Geerling
https://leanpub.com/ansible-for-devops


## Running the playbook

Place details about running your playbook here 


ansible-playbook playbook.yml -i hosts -u username -k -v

## Notes:
Using the {{ inventory_hostname variable }} vs the {{ ansible_hostname }}
````
 ________________________________________
/ inventory_hostname variable - This is  \
| the host name we use to connect to the |
\ server.                                /
 ----------------------------------------
        \   ^__^
         \  (oo)\_______
            (__)\       )\/\
                ||----w |
                ||     ||
                
 ____________________________________
/ ansible_hostname - refers to the   \
\ hostname set on the server itself. /
 ------------------------------------
  \
   \
       __
      UooU\.'@@@@@@`.
      \__/(@@@@@@@@@@)
           (@@@@@@@@)
           `YY~~~~YY'
            ||    ||
````

