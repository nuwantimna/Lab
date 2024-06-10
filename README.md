# Lab
Practice Lab Setup
To create a practice lab using Vagrant, follow these steps:

Install Vagrant: Ensure that Vagrant is installed on your system. You can download and install it from the official website.

Create a Directory: Create a directory for your Vagrant project.

Initialize Vagrant: Inside the project directory, create a new file named Vagrantfile. This file will contain the configuration for your Vagrant environment.

Configure Vagrantfile: Open the Vagrantfile in a text editor and add the following configuration:

Run Vagrant: Save the Vagrantfile and return to your terminal. Navigate to the project directory and run vagrant up. Vagrant will download the specified box images and create the virtual machines according to the configuration in the Vagrantfile.

Access the Machines: Once the machines are up and running, you can SSH into them using vagrant ssh [machine-name]. For example, vagrant ssh app1 will SSH into the first application server.

That's it! You now have a practice lab set up with multiple virtual machines using Vagrant. You can customize the configuration further to meet your specific requirements.
