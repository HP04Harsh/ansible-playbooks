# Ansible Playbooks

A collection of practical Ansible playbooks for automating common Linux administrative tasks.

## Overview
This repository contains reusable automation scripts to streamline DevOps tasks, ranging from basic system configuration to software deployment.

## Included Playbooks
* **`copy_file.yaml`**: Automates file distribution across managed nodes.
* **`download_remote_file.yaml`**: Fetches files from remote sources to target servers.
* **`file_create.yaml`**: Standardizes file and directory creation.
* **`install_nginx.yaml`**: Automates the installation and setup of the Nginx web server.
* **`loop.yaml`**: Demonstrates the use of loops for repetitive task automation.
* **`notify_handlers.yaml`**: Demonstrates using handlers to trigger actions after configuration changes.
* **`script_run.yaml`**: Executes custom shell scripts on target hosts.
* **`user_creation.yaml`**: Simplifies bulk user management and system account creation.

## Prerequisites
- [Ansible](https://docs.ansible.com/) installed on your control node.
- SSH access configured for target hosts.

## Usage
1. Define your target hosts in an `inventory.ini` file.
2. Run a playbook using the following command:

```bash
ansible-playbook -i inventory.ini <playbook_name>.yaml
```

### **Markdown Syntax Cheat Sheet**
If you want to customize your README further, here are the most useful Markdown elements:

* **Headers:** Use `#` for the title, `##` for main sections, and `###` for sub-sections.
* **Emphasis:** Wrap text in `**bold**` or `*italics*`.
* **Lists:** Use `*` or `-` for bullet points.
* **Code Blocks:** Wrap code in triple backticks (\`\`\`) to create syntax-highlighted blocks.
* **Inline Code:** Wrap text in single backticks (\`) for `commands` or file names.
* **Links:** Use `[Link Text](URL)` to create clickable links.

Would you like me to help you create a sample `inventory.ini` file to go along with these playbooks?

