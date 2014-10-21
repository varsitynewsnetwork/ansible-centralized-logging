Ansible Centralized Logging
===========================
A collection of ansible roles designed to make deploying
a centralized logging server super easy.

It has configurations for configuring the central log server (broker/indexer), as well as configurations for all the shippers.

This uses Logstash and Elasticsearch for the central server, Logstash Forwarder for the shippers, and Kibana running on Nginx for the UI

Built for CentOS 6.5

Run this playbook with:

```
ansible-playbook -i hosts -l forwarder_hosts -K play.yml
```
