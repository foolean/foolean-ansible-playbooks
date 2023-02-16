# foolean-ansible-playbooks

Collection of Foolean playbooks


## Usage

    * clone this repo into '/path/to/your/ansible/playbooks/foolean'
    * run `git submodule update --init


## Ansible structure

    ansible/          <-- foolean-ansible super-project
    |-- inventory/
    |   |-- group_vars/
    |   `-- host_vars/
    |-- playbooks/
    |   `-- foolean/  <-- foolean-ansible-playbooks repo
    `-- roles/
        `-- foolean/  <-- foolean-ansible-roles super-project


## License

BSD-3-Clause
