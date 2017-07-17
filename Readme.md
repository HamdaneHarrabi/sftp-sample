Client setup
============

Copy the ssh key from the client to the serve

$ ssh-copy-id sftpuser@sftp.example.hostname

Les axes d'amélioration
=======================

1- config firwall flux I/O

2- rsyslog

3- utilisation d'ansible-vault pour le password
 
Tests
=========

Création d'un script pyhton ou playbook ansible(module docker) de test qui permet de faire:

 1- Un pull d'une image docker centos 7
 
 2- Création container docker
 
 3- Exécuter le role sftp sur le container
 
 4- Tester que le user créé ne peut pas se connecter en ssh
 
 5- Tester que le user créé ne peut pas aller dans le répertoire /etc en se connectant en sftp 
 
 
 
