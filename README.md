Ansible with Docker provisioning
=================================

This is an Ansible template to run tests against local Docker container.

It's a 2 steps process, provision the docker locally and run tasks against the registered docker host.

How to run
-----------

ansible-playbook docker.yml

Requirements
------------

- You should install anaconda environment for easy testing
- pip install -r requirements.txt

License
-------

BSD