# Ansible-Development
Repo to create an Ansible development server

If you are able to utilize collections in your environment, use ansibleserver.yml

If you have only installed ansible-core, utilize ansibleserver_usingbuiltinmodules.yml

Update the variables at the top of the playbook you choose in order to set up an environment for a specific user that already exists on a VM
1. Download and install code-server to run on a specific port (must select a different port per user)
1. Establish ssl certs for web page (if desired)
1. Install podman, git, and ansible-navigator
1. Set up subuid and subgid for podman
1. Pull in desired execution environment using registry username and password
1. Set up ansible-navigator, code-server, and the ansible-extension with requested EE and base settings
1. Establish a directory structure
1. Deploy an inventory/host/group vars if desired
1. Deploy an example repository with a role structure if desired (https://github.com/shadowman-lab/Ansible-Example)

## Troubleshooting

- make sure other can read /etc/pki/tls/certs