# Ansible
1. What is Ansible?
Ansible is an open-source automation tool that simplifies the process of configuration management, application deployment, task automation, and orchestration. It allows you to define and describe the infrastructure and application environments in a declarative manner, using simple, human-readable YAML files. Ansible uses SSH to connect to servers and does not require any agent installation on the managed nodes.

2. Ansible Architecture:
Ansible follows a client-server architecture, but it's agentless. The key components include:

Control Node: The machine where Ansible is installed and from which automation tasks are run.
Managed Nodes: The remote servers or devices that are managed by Ansible. No agent is required on managed nodes.
Inventory: A file or files that specify the managed nodes and their connection details.
Modules: These are units of work that Ansible executes. They are small scripts or pieces of code that perform specific tasks.
Playbooks: Descriptions of desired system states written in YAML format.
3. Why Ansible is Popular Over Other Configuration Management Tools:
Agentless: Ansible doesn't require agents on managed nodes, making it simpler to set up and manage.
Simple and Human-Readable: Ansible uses YAML syntax, making it easy to read and write, even for those who are not programmers.
Extensibility: Ansible can be easily extended with custom modules and plugins.
Large Community: Ansible has a large and active community, providing support, sharing modules, and contributing to the tool's growth.
4. Ansible Ad-Hoc Commands:
Ad-hoc commands are one-liners used for quick tasks without the need to create a playbook. They are executed from the command line. 

5. Ansible Playbooks:
Playbooks are Ansible's configuration, deployment, and orchestration language. They are written in YAML and define a series of tasks to be executed on specified hosts. Playbooks allow you to express configuration in a more comprehensive and organized way compared to ad-hoc commands.

6. Difference Between Ad-Hoc and Ansible Playbooks:
Ad-Hoc: Quick, one-off commands for simple tasks.
Playbooks: More structured, allowing you to define complex tasks, dependencies, and conditions. Suitable for configuration management and application deployment.
7. Roles in Ansible and Why They Are Used:
Roles are a way to organize and structure playbooks, making them reusable and more modular. They encapsulate related tasks, variables, and handlers into a directory structure. Roles simplify playbook maintenance and promote code reuse, especially when managing multiple systems or projects with similar configurations.
