# AWS Infrastructure Automation using EC2 and Ansible

A multi server setup on AWS EC2: 1 control node and 2 managed nodes, managed with Ansible.

## What is done
- Launched 3 EC2 instances (1 control node, 2 target nodes)
- Set up passwordless SSH key authentication from the control node to both targets
- Created an Ansible inventory file for the target servers
- Verified connectivity with `ansible all -m ping`, and both servers returned `pong`

## Tools
AWS EC2, Ansible, Ubuntu, SSH, Git

 Wrote an Ansible playbook that installs and starts nginx on both target servers
