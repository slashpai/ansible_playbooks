# msteams_ansible

* Ansible playbook utilizing role [ansible-prometheus-msteams](https://github.com/slashpai/ansible-prometheus-msteams)

## Usage

* [Vagrantfile](Vagrantfile) can be used to provision machine first by running `vagrant up` and then apply playbook to the machine using `ansible-playbook msteams_playbook.yml`

* Once playbook run is completed, hit the browser http://192.168.33.100:2000/config to verify or use curl

Refer [here](https://stackoverflow.com/questions/3796927/how-to-git-clone-including-submodules) to see how to clone repo with submodule
