* Client setup *
	Copy the ssh key from the client to the serve
	$ ssh-copy-id sftpuser@sftp.example.hostname


* Les axes d'am�lioration * 
 1- config firwall flux I/O
 2- rsyslog
 3- utilisation d'ansible-vault pour le password
 
* tests *

Cr�ation d'un script pyhton ou playbook ansible(module docker) de test qui permet de faire:

 1- Un pull d'une image docker centos 7
 2- Cr�ation container docker
 3- Ex�cuter le role sftp sur le container
 4- Tester que le user cr�� ne peut pas se connecter en ssh
 5- Tester que le user cr�� ne peut pas aller dans le r�pertoire /etc en se connectant en sftp 
 
 
 