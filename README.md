# Mark-4
ansible playbook for installing, starting
### To run the playbook
~~~
ansible-playbook -i <inventory_file>  <playbook.yml file>
~~~
### To manualy run a commands
~~~
ansible -i <inventory_file> all -m  "shell" -a "touch dev"
~~~

# ans-mark-4.1
To install,run,and checking status of nginx on ec2 instance

The server is placed in inventory file and ssh connectivity should be in place between those two servers.

# ans-mark-4.3

To install apache 2 web service in the ubuntu instance

we will also install, run, launch and simple html web page 

# ans-mark-4.4

launch an ec2 and connect with that instance with shared "Key pair assigned at launch" and with ansible. we will install and configure mysql db in it.

First we update the instance, then install mysql, and we install python3 in virtual env and install build dependeces for sqlcli

 
