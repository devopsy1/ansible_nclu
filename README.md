# Cumulus Linux NCLU Module for Ansible
This Git Repo is about Backing up Existing Configurations and replaying them back to your gear with the NCLU module.  Click this link for more info on the [Cumulus Networks NCLU Module](http://docs.ansible.com/ansible/latest/nclu_module.html)

![Graphic Illustrating Push and Pull playbooks for NCLU commands][pushpull.png]

## Background Info

Prior to the Cumulus Networks NCLU Module for Ansible I wrote this Knowledge Base article on backup and restoring configs on Cumulus Linux here: [https://support.cumulusnetworks.com/hc/en-us/articles/209620358-Ansible-Backing-up-Existing-Configurations](https://support.cumulusnetworks.com/hc/en-us/articles/209620358-Ansible-Backing-up-Existing-Configurations).  This way will still work but for those who want to use the NCLU module and net command soley and not keep track of which files they are touching this gives an alternate method.
