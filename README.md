# README #

This is a template Ansible playbook structure
It is designed to be the base for new Ansible Playbook projects

Change this to an update for your project



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

