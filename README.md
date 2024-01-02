# Ansible-Advance
This repo contains Advanced Ansible learnings

### Table of Content

* 01-Introduction
    * [01-Ansible Basics](https://github.com/nilanjanb3/ansible)
* 02-Core Components
    * [01-"--check" flag](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_intro.html#running-playbooks-in-check-mode)
    * [02-"--start-at-task <task-name>" flag](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_startnstep.html#start-at-task)
    * [03-"--tags"](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_tags.html#selecting-or-skipping-tags-when-you-run-a-playbook)
    * [04-Ansible Facts](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_vars_facts.html)
    * [05-Config File](https://docs.ansible.com/ansible/latest/reference_appendices/config.html)
    * [06-More on Ansible Facts](https://www.middlewareinventory.com/blog/ansible-facts-list-how-to-use-ansible-facts/)
* 03-Install and Configuration
    * [01-Installing Ansible](https://docs.ansible.com/ansible/latest/installation_guide/installation_distros.html)
    * [02-Generating SSH Key and Distributing to VMs](https://learn.microsoft.com/en-us/azure/virtual-machines/linux/create-ssh-keys-detailed#use-ssh-copy-id-to-copy-the-key-to-an-existing-vm)
    * [03-Using Ansible Ad-Hoc Commands](https://docs.ansible.com/ansible/latest/command_guide/intro_adhoc.html#check-mode)
    * [04-Ping Command to Check SSH Connection to Hosts](https://www.freekb.net/Article?id=3008)
    * [05-Ad-Hoc Examples We Can Include in Shell Scripts](https://www.middlewareinventory.com/blog/ansible-ad-hoc-commands/)
    * [06-Privilege Escalation](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_privilege_escalation.html)
    * [07-loop Vs with_items](https://italchemy.wordpress.com/2021/07/23/ansible-with_items-vs-loop-whats-the-difference/comment-page-1/)
* 04-Ansible Modules
    * [01-apt module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/apt_module.html)
    * [02-yum module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/yum_module.html)
    * [03-package module (dynamically takes decession)](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/package_module.html)
    * [04-service module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/service_module.html)
    * [05-firewalld module](https://docs.ansible.com/ansible/latest/collections/ansible/posix/firewalld_module.html)
    * [06-lvg module](https://docs.ansible.com/ansible/latest/collections/community/general/lvg_module.html)
    * [07-lvol module](https://docs.ansible.com/ansible/latest/collections/community/general/lvol_module.html)
    * [08-filesystem module](https://docs.ansible.com/ansible/latest/collections/community/general/filesystem_module.html)
    * [09-mount module](https://docs.ansible.com/ansible/latest/collections/ansible/posix/mount_module.html)
    * [10-file module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/file_module.html)
    * [11-archive module](https://docs.ansible.com/ansible/latest/collections/community/general/archive_module.html)
    * [12-unarchive module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/unarchive_module.html)
    * [13-cron module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/cron_module.html)
    * [14-user module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/user_module.html)
    * [15-group module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/group_module.html)
    * [16-authorized_key module](https://docs.ansible.com/ansible/latest/collections/ansible/posix/authorized_key_module.html)
* 05-Variables and Jinja 2
    * [01-Ansible Variables](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_variables.html)
    * [02-Variable Precedance](https://medium.com/trendfingers/variable-precedence-in-ansible-2a3dba7766ab)
    * [03-Variable Scope](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_variables.html#scoping-variables)
    * [04-Using Register to Store Variable](https://linuxhint.com/ansible_register_module/)
    * [05-Ansible Special Variables](https://docs.ansible.com/ansible/2.7/reference_appendices/special_variables.html# )
    * [06-Jinja 2 Basics](https://linumary.medium.com/jinja2-basics-2b0bd283f6a)
    * [07-Ansible Filters](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_filters.html)
    * [08-Templating Using Jinja 2](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_templating.html)
* 06-Playbook Flow
    * [01-Using Conditional](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_conditionals.html)
    * [02-Using Blocks](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_blocks.html)
    * [03-Error Handling](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_error_handling.html)
    * [04-Ansible Execution Strategy](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_strategies.html)
* 07-Include and Roles
    * [01-Ansible Directory Structure](https://docs.ansible.com/ansible/2.8/user_guide/playbooks_best_practices.html#alternative-directory-layout)
    * [02-include_vars Module](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/include_vars_module.html)
    * [03-ansible-inventory command](https://docs.ansible.com/ansible/latest/cli/ansible-inventory.html)
    * [04-include_task Module](https://www.toptechskills.com/ansible-tutorials-courses/ansible-include-import-tasks-tutorial-examples/)
    * [05-What is Role in Ansible?](https://docs.ansible.com/ansible/latest/playbook_guide/playbooks_reuse_roles.html)
    * [06-Ansible Galaxy](https://galaxy.ansible.com/ui/)
    * [07-Ansible Galaxy Commands](https://docs.rockylinux.org/books/learning_ansible/04-ansible-galaxy/)
* 08-Miscellaneous
    * [01-Ansible Vault](https://docs.ansible.com/ansible/2.9/user_guide/vault.html)
    * [02-Dynamic Inventory](https://docs.ansible.com/ansible/latest/inventory_guide/intro_dynamic_inventory.html)
    * [03-Setting EC2 Dynamic Inventory](https://devopscube.com/setup-ansible-aws-dynamic-inventory/)
    
    
