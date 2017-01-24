# Ad-Hoc
## Quiz
1.  What is an Ad-Hoc command?

  * One time (fire and forget) command
  * Command to list playbooks
  * Command to show service status of Ansible
  * None of the above

2. You do not need inventory file for running Ad-Hoc commands.

  * True
  * False

3. Ad-Hoc commands are recommended for setting up an environment (eg. IDE)

  * True
  * False

4. How do you ping all the machines using Ansible

  * ansible ping all
  * ansible -m ping all
  * ansible all -m ping
  * ansible all -a ping

5. What is an inventory file?

  * File in which machines are grouped according to their roles
  * Ansible configuration file
  * SSH configuration file
  * A copy of /etc/hosts file

6. Inventory file format is like

  * YAML like
  * XML like
  * JSON like
  * INI like

7. What are the requirements of Ad-Hoc commands?

  * Controller and nodes should be ping-able
  * Controller is capable of ssh-ing into nodes
  * Python should be present on all the machines
  * All of the above

8. Which statement is true from the following?

  * Inventory file should have .ini extension
  * Ad-Hoc can be used for big configuration tasks
  * It is not possible to execute Ad-Hoc command for a specific inventory group
  * None of the above

9. How do you debug in Ad-Hoc command?

  * Using -debug option
  * Using -l (logging) option
  * Using -vvv (verbose) option
  * By viewing log file

10. Does Ansible have log file by default?

  * True
  * False
