# Webserver_deployed_Ansible
Running this playbook will perform the following actions on your Ansible hosts:

Install aptitude, which is preferred by Ansible as an alternative to the apt package manager.
Install Apache.
Create a custom document root folder for the new Apache VirtualHost and set up a test page.
Enable the new Apache VirtualHost.
Disable the default Apache website when the variable disable_default is set to true.
Set up UFW to allow HTTP traffic on the configured port (80 by default).
