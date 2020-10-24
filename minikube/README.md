# minikube

* Ansible playbook utilizing role [ansible-minikube](https://github.com/slashpai/ansible-minikube)

## Usage

* [Vagrantfile](Vagrantfile) can be used to provision machine first by running `vagrant up` and then apply playbook to the machine using `ansible-playbook minikube.yml`

To execute on vagrant machine

  ```python
  ansible-playbook minikube.yml -l vagrant
  ```

To execute on local machine

  ```python
  ansible-playbook minikube.yml -l local_machine --ask-become-pass
  ```
