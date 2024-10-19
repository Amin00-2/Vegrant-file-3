STEP BY STEP GUIDE IN INSTLLING VAGRANT AND VIRTUAL BOX

1. Download and Install VirtualBox
Vagrant requires a provider to run virtual machines. For most users, VirtualBox is the easiest provider to use. Here's how to install it:
•	Step 1: Go to the VirtualBox download page.
•	Step 2: Under "VirtualBox platform packages," click on the link for Windows hosts to download the installer.
•	Step 3: Once downloaded, run the installer and follow the prompts. The default settings should work for most cases.
2. Download and Install Vagrant
Next, you need to install Vagrant itself.
•	Step 1: Go to the Vagrant official website.
•	Step 2: Under the "Windows" section, click the "64-bit" version to download the installer.
•	Step 3: Run the Vagrant installer and follow the instructions. Accept the license agreement and leave the default installation path.

3   Verify Installation of Vagrant
After installation, verify that Vagrant is correctly installed:
•	Step 1: Open a command prompt (Win + R, type cmd, and press Enter).
•	Step 2: Type the following command to check if Vagrant is installed properly:

4. Initialize Vagrant in a Directory
Now that Vagrant is installed, you can initialize a project.
•	Step 1: Create a new folder where you want your Vagrant project to reside. You can use the File Explorer or the command line.
•	Step 2: Open a command prompt in that directory or navigate to it using
•	Step 3: Initialize a Vagrantfile (a configuration file for your Vagrant environment) with the following command:


 5 Launch a Vagrant Machine
Now that your Vagrantfile is set up, you can start the virtual machine (VM).
•	Step 1: Open the Vagrantfile and find the line that specifies the box (this is the virtual machine image). By default, it will be set to use hashicorp/bionic64. You can leave this as is for now.
•	Step 2: Start the virtual machine using:
vagrant up
![alt text](vagrant is up and running manually in vscode.png)

![alt text](vagrant SSH.png)

![alt text](vegrant is installed.png)

![alt text](vagrant up.jfif)

![alt text](Vagrant file .png)

![alt text](vv.jfif)




