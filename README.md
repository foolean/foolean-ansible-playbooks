# foolean-ansible-playbooks

    Collection of Foolean playbooks


## Usage

    * clone this repo into '/path/to/your/ansible/playbooks/foolean'


## Playbooks

    os.yml          Base operating system playbook
    os-test.yml     Base operating system "testing" playbook


## Expected structure

    ansible/
    |-- inventory/
    |   |-- group_vars/
    |   `-- host_vars/
    |-- playbooks/
    |   `-- foolean/  <-- foolean-ansible-playbooks repo
    `-- roles/
        `-- foolean/  <-- foolean-ansible-roles super-project


## License

    BSD-3-Clause
