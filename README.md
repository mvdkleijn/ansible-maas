# ansible-maas

An Ansible Dynamic Inventory Script for the Ubuntu MAAS 2.0 API.

Primarily it will be called by Ansible itself with the `--list` or `--host`
arguments, but additional arguments were implemented for administrators to take
advantage of if desired.

Note: this script will only return machines that are in "Deployed" status.

## Usage

- Replace Ansible's hosts file in the correct directory, e.g. `/etc/ansible/hosts`
- Set environment variables `MAAS_API_URL` and `MAAS_API_KEY`
- Enjoy!
