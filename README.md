# Autopsy multicluster Automation

## Description
The purpose of this repository is to share resources for providing multiple methods on how to install/setup an Autopsy multi-client cluster.
Blog post about it is available here: [Getting started with Autopsy multi-user cluster](https://holdmybeersecurity.com/2021/05/11/getting-started-with-autopsy-multi-user-cluster/).

This blog post generated an infrastructure-as-code in the form of an Ansible playbook, Docker-compose, and manual instructions for setting up a cluster.
In addition, this blog post will demonstrate how to setup the Autopsy client to connect to the Autopsy cluster and how to ingest disk images.

## References
### Ansible
* [How to check if a file exists in Ansible?](https://stackoverflow.com/questions/35654286/how-to-check-if-a-file-exists-in-ansible)
* [ansible.builtin.unarchive](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/unarchive_module.html)
* [ansible.builtin.get_url](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/get_url_module.html)
* [ansible.builtin.stat](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/stat_module.html)
* [ansible.builtin.file](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/file_module.html)
* [ansible extract without first directory](https://unix.stackexchange.com/questions/346346/ansible-extract-without-first-directory)
* [ansible.builtin.wait_for](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/wait_for_module.html)
* [ansible.builtin.apt_key](https://docs.ansible.com/ansible/latest/collections/ansible/builtin/apt_key_module.html)
* [community.general.ufw](https://docs.ansible.com/ansible/latest/collections/community/general/ufw_module.html)
* [postgresql_user](https://docs.ansible.com/ansible/2.5/modules/postgresql_user_module.html)

### Autopsy
* [sourceforge - Autopsy](https://sourceforge.net/projects/autopsy/)

### ActiveMQ
* [DockerHub - rmohr/activemq](https://hub.docker.com/r/rmohr/activemq)
* [Autopsy docs - Install and Configure ActiveMQ](http://sleuthkit.org/autopsy/docs/user-docs/4.18.0/install_activemq_page.html)
* [How to Install Apache ActiveMQ on Ubuntu 18.04 | 16.04](https://websiteforstudents.com/how-to-install-apache-activemq-on-ubuntu-18-04-16-04/)

### Postgres
* [DockerHub - postgres](https://hub.docker.com/_/postgres?tab=description)
* [Autopsy docs - Install and Configure PostgreSQL](http://sleuthkit.org/autopsy/docs/user-docs/4.18.0/install_postgresql_page.html)
* [StackOverFlow - How to customize the configuration file of the official PostgreSQL Docker image?](https://stackoverflow.com/questions/30848670/how-to-customize-the-configuration-file-of-the-official-postgresql-docker-image/41912295)
* [gcc error installing psycopg2 package for python3 on Centos 7.3](https://unix.stackexchange.com/questions/345814/gcc-error-installing-psycopg2-package-for-python3-on-centos-7-3)
* [Linux downloads (Ubuntu)](https://www.postgresql.org/download/linux/ubuntu/)
* [Install PostgreSQL 9.5 step by step](https://www.gab.lc/articles/install_postgresql_9-5_debian_ubuntu/)
* [How to set postgres password using ansible](https://stackoverflow.com/questions/63303090/how-to-set-postgres-password-using-ansible)
* [Ansible create postgresql user with access to all tables?](https://stackoverflow.com/questions/40290837/ansible-create-postgresql-user-with-access-to-all-tables)
* [Configure PostgreSQL to allow remote connection](https://bigbinary.com/blog/configure-postgresql-to-allow-remote-connection)
* [Granting a user account permission to create databases in PostgreSQL](https://dba.stackexchange.com/questions/33285/granting-a-user-account-permission-to-create-databases-in-postgresql)

### Zookeeper
* [Configuration for a ZooKeeper Ensemble](https://solr.apache.org/guide/8_6/setting-up-an-external-zookeeper-ensemble.html#configuration-for-a-zookeeper-ensemble)
* [How To Install and Configure an Apache ZooKeeper Cluster on Ubuntu 18.04](https://www.digitalocean.com/community/tutorials/how-to-install-and-configure-an-apache-zookeeper-cluster-on-ubuntu-18-04)
* [Installing Zookeeper on Ubuntu](https://medium.com/@ryannel/installing-zookeeper-on-ubuntu-9f1f70f22e25)
* [How to choose directory name during untarring](https://unix.stackexchange.com/questions/11018/how-to-choose-directory-name-during-untarring)

### Samba
* [samba sync password with unix password on debian wheezy](https://superuser.com/questions/478521/samba-sync-password-with-unix-password-on-debian-wheezy)
* [Autopsy - Set Up Shared Storage](http://sleuthkit.org/autopsy/docs/user-docs/4.18.0/install_multiuser_storage_page.html)
* [Building An Incident Response And Forensics Homelab — PT1: Workstation And File Storage](https://medium.com/@liamcs98/building-an-incident-response-and-forensics-homelab-pt1-workstation-and-file-storage-e23eca7ea57a)

### Solr
* [Apache Solr v8.6.3 - TAR download](https://archive.apache.org/dist/lucene/solr/8.6.3/)
* [Installing OpenJRE](https://ubuntu.com/tutorials/install-jre#2-installing-openjre)
* [Solr log file location on Ubuntu](https://serverfault.com/questions/279505/solr-log-file-location-on-ubuntu)
* [StackOverFlow - How to automatically start a service when running a docker container?](https://stackoverflow.com/questions/25135897/how-to-automatically-start-a-service-when-running-a-docker-container)
* [su options - running command as another user](https://unix.stackexchange.com/questions/1087/su-options-running-command-as-another-user)
* [Github - docker-solr/docker-solr](https://github.com/docker-solr/docker-solr)
* [StackOverFlow - How to split a delimited string into an array in awk?](https://stackoverflow.com/questions/8009664/how-to-split-a-delimited-string-into-an-array-in-awk)
* [Getting Started with SolrCloud](https://solr.apache.org/guide/6_6/getting-started-with-solrcloud.html)
* [Setting up Solr Cloud 8.4.1 with Zookeeper 3.5.6](https://medium.com/@sarkaramrit2/setting-up-solr-cloud-6-3-0-with-zookeeper-3-4-6-867b96ec4272)
* [Taking Solr to Production](https://solr.apache.org/guide/6_6/taking-solr-to-production.html#TakingSolrtoProduction-SolrCloud)
* [How to Install Apache Solr on Ubuntu 20.04](https://www.howtoforge.com/apache-solr-ubuntu-20_04/)
