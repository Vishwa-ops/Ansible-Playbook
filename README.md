Ansible Playbook:
This repository contains Ansible playbooks for automating common system administration tasks.  
All playbooks are tested on Ubuntu

Playbooks Included:
1) first_demo_pb.yml - Basic demo playbook to test Ansible setup
2) installing_packages.yml - Installs packages (like nginx, apache, etc.)
3) copy_file_from_remote.yml - Copies files from local to remote servers
4) creating_file_folder_remote.yml - Creates files and directories on remote servers
5) script_running_remote.yml - Runs shell scripts on remote servers
6) cron_job.yml - Creates new cron jobs
7) cron_modify.yml - Modifies existing cron jobs
8) cron_env_modify.yml - Modifies cron environment variables
9) user_mng.yml - Creates and manages users
10 user_mng_passwd_set.yml - Sets or updates user passwords
11) kill_the_process.yml - Kills unwanted processes on remote servers
12) Downloading_file_internet.yml - Downloads files from the internet
13) enabled_service_firewall.yml - Enables and configures firewall services

How to run the playbook:
ansible-playbook <playbook-name>.yml
example: ansible-playbook installing_packages.yml
