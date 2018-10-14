# Ansible AWS Infrastructure & Code Deployment automation

Scripts in this repo perform the following:
1. Create a "nodejs" role for installing nodejs and npm on an AWS t2.micro ec2 instance.
2. Create a "helloworld" role for copying a helloworld.js script to be ran on the node server, copying an upstart configuring file to deamonize our helloworld application, configure a task to start the helloworld application, create a handler to restart the helloworld app and add a "nodejs" role dependancy to the "helloworld" role.
