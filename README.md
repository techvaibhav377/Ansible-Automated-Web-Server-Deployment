# **Automated Web Server Deployment with Ansible**
**Read All Instruction Carefully Before Start this project and make changes in file as per your requirements**

## **Introduction**
This document provides a comprehensive guide to deploying a web server using Ansible. The project involves setting up a web server, configuring virtual hosts for multiple subdomains, and transferring files to the server.

## **Prerequisites**

- **Ansible installed on the control node.**
- **Access to target servers via SSH.**
- **Knowledge of basic Ansible concepts such as playbooks, tasks, and variables.**

## **Directory Structure**

- **playbooks/:** Contains Ansible playbooks.
- **template/:** Stores Jinja2 template files.
- **vars.yml:** Variable file containing configuration details.

## **Ansible Configuration** 
**Ensure Ansible is properly configured with SSH keys or password authentication for remote server access. Update ansible.cfg with necessary settings such as inventory path and privilege escalation options.**

## **Check All Playbooks CareFully Before Run**

## **Project Structure**

- **ansible.cfg:** Ansible configuration file.
- **hosts:** Inventory file of remote host IP.
- **vars.yml:** Variable file for j2 and playbook.
- **passwordless_authentication.yml:** Tasks for making a passwordless connection in Ansible.
- **web.yml:** Tasks for installing the web server and creating a document root directory for subdomains.
- **indexfile.yml:** Tasks for deploying index.html file in respective subdomain document root.
- **virtualhost.j2:** Virtual hosting file template.

## **Conclusion**

**This project demonstrates the automation of web server deployment using Ansible. By leveraging Ansible's capabilities, administrators can efficiently manage server configurations and streamline deployment processes.**

**Author: Vaibhav Gautam**
