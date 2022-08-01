#  Ansible Playbook / Baseline Health Check
generate health check report to support issue tracking by writing ansible playbook

## Install VirtualBox
1. Open the VirtualBox website https://www.virtualbox.org/  
2. Click Download VirtualBox It's a blue button in the middle of the page. Doing so will open the downloads page
3. Click OS X hosts  **download onto your Mac
4. Open the "VirtualBox" DMG file double-click the file to open
5. Double-click the "VirtualBox.pkg" icon
6. Navigate through the installation prompts
* Click Continue in the bottom-right 
* Click Install in the bottom-right
* Enter your Mac user password
* Click Install Software
7. Wait for the installation to complete. Once you're prompted to click Close in the bottom-right corner of the window, you've successfully installed VirtualBox on your Mac

## Install Ansible on VirtualBox
Install pip if not present 
* sudo yum install epel-release
* sudo yum install python-pip

Install Ansible using pip
* sudo pip install ansible

Upgrade Ansible using pip
* sudo pip install --upgrade ansible

Install Specific Version of Ansible using pip
* sudo pip install ansible==2.4

Check Version Ansible 
* ansible --version

## Example Playbook
```
-
 name: "CIS CentOS 7"
 hosts: all
 tasks:
   - name:
```
