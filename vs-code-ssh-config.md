###VScode-ssh-config

Create key:
	
	ssh-keygen -t rsa
	ssh-copy-id ansadmin@192.168.0.182

update VScode config:

	ssh -i ~/.ssh/id_rsa ansadmin@192.168.0.182


Config file: 

	Host 192.168.0.182
		User ansadmin
		HostName 192.168.0.182
		IdentityFile ~/.ssh/id_rsa