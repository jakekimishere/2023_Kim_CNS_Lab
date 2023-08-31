# **Homework 1 Submission**
# Name: Jake Kim
# Class: Computer and Network Security
# Date: 31 August 2023
# **--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------**
# 1. Completed in CNS repository 

# 2. Completed in CNS repository

# 3. Completed below:
##  Provision a Virtual Machine Tutorial
### This tutorial demonstrates the process of provisioning a virtual machine using Vagrant. 
### Step 1: Create HTML directory: Make a local "HTML" directory.
### Step 2: Provisioning Script: Created "bootstrap.sh" to install Apache and set up a symlink to serve content.
### Step 3: Vagrant Configuration: Edit the Vagrantfile to use the provisioning script. 
### Step 4: Verify Deployment: SSH into the guest machine and check that the website is active by accessing it through '127.0.0.1'.
### The tutorial demonstrates how Vagrant streamlines environment setup and allows serving content on a machine's webserver.
![Screenshot for provisioning a VM.](/../main/assets/images/CNS_HW1.png)
##  Configure the Network Tutorial
### This tutorial shows the steps to configure networking using Vagrant to enable access to the guest machine to the host machine.
### Step 1: Configure Port Forwarding: Modify Vagrantfile by adding a 'config.vm.network' and forwarding guest port 80 to host port 4567.
### Step 2: reloading the VM with 'vagrant reload'
### Step 3: access 'http://127.0.0.1:4567' to the web page in your browser.
### This shows Vagrant's ability to bridge the guest and host machine.
![Screenshot for Configuring the Network.](/,,/main/assets/images/CNS_HW!_2.png)
# 4. Vagrant provisioner: Shell Provisioner
## Let you run and manage scripts inside a virtual guest machine created using Vagrant. Two main methods: You write down the instructions directly 
## in your Vagrant setup file with "inline" scripting, or you give it a file with all the instructions. 
## For POSIX-like operating systems, the shell provisioner uses SSH to execute scripts.
## While Windows guest machines are configured with WinRM, use PowerShell and Batch scripts over WinRM.
## Overall, Shell Provisioner can be used for both simple and elaborate provisioning by letting you talk it through scripts.
