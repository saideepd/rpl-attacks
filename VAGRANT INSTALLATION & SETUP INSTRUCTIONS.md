1. Clone this repository<br>
$ ``git clone https://github.com/dhondta/rpl-attacks.git``

2. Download **Vagrant for Debian** from this site:<br>
https://www.vagrantup.com/downloads.html

3. Install the downloaded Vagrant software by double clicking the package and clicking Install button

4. Also use this command once to ensure everything is properly installed<br>
$ ``sudo apt install vagrant``

5. Create an account for Vagrant on this site:<br>
https://app.vagrantup.com/account/new

6. Verify the account by email verification mail

7. Change the directory to your<br>
$ ``cd ~/rpl-attacks/folder/``

8. Delete or Rename the existing Vagrant file in rpl-attacks folder

9. Run this command after deleting/renaming vagrant file<br>
$ ``vagrant init dhondta/rpl-attacks --box-version 1.0.0``

10. Download & Install Virtual Box from this link<br>
https://www.virtualbox.org/wiki/Linux_Downloads

11. Download & Install Oracle Extension Pack from this link:<br>
https://download.virtualbox.org/virtualbox/5.2.22/Oracle_VM_VirtualBox_Extension_Pack-5.2.22.vbox-extpack

12. Create the VM<br>
$ ``vagrant login``

13. Enter your Username & Password

14. Then simply download the Vagrant Box for rpl-attcks by running this command<br>
$ ``vagrant up --provider virtualbox``

**IMPORTANT NOTE:**<br>
> The downloads of the Vagrant box may take a while, please be patient.<br />
> Also, after the creation of the VM, Vagrant may complain that the SSH connection was unexpectedly closed by the remote end. In practice, this does not affect the creation and operation of the box.


15. Open Virtual Box and open the _**rpl-attacks Virtual Machine**_

17. Open **Terminal** and **cd ~/to/rpl-attacks/folder/** in VM

18. Run the command<br>
$ ``fab demo``

19. The sample attacks must have started creating and simulating the campaign on its own

20. You'll find the results in **Experiments folder** in Home directory.


If you face issues, try solutions from this link: https://github.com/hashicorp/vagrant/issues/7969
