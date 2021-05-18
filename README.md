# ansiblescript-automation

File Encryption
To create a new encrypted file named secrets.yml, simply use the following ansible-vault command.

	ansible-vault create secrets.yml

Decrypting Encrypted Files
If you want to decrypt an encrypted file, you can use ansible-vault decrypt command.
	
	ansible-vault decrypt secrets.yml

Decrypting Encrypted Files During Runtime
If you wish to decrypt a file during runtime, you could use –ask-vault-pass flag.

	ansible-playbook launch.yml --ask-vault-pass
	ansible-playbook -i node_hosts git_repository.yaml --ask-vault-pass

------------------------------------------------------

Ansible lookup file – How to Read file into variable in Ansible

	LINK - 	https://www.middlewareinventory.com/blog/ansible-lookup-file/

ansible update /etc/hosts file with IP of all hosts across all hosts
	
	LINK - https://www.middlewareinventory.com/blog/ansible-update-etc-hosts-file-across-all-hosts/

Setup SSH Key and initial user using Ansible Playbook

	LINk - https://devops4solutions.medium.com/setup-ssh-key-and-initial-user-using-ansible-playbook-61eabbb0dba4


