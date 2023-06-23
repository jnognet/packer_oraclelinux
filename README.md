Learned:
	https://github.com/alvistack/vagrant-ubuntu
	https://github.com/mrlesmithjr/packer-templates

Readed: 
	https://docs.oracle.com/en/operating-systems/oracle-linux/8/install/install-AutomatinganOracleLinuxInstallationbyUsingKickstart.html#auto-ks
	https://pykickstart.readthedocs.io/en/latest/kickstart-docs.html#id2

Using:
	- Pop!_OS 22.04 LTS 
	- OracleLinux-R8-U8-x86_64-dvd.iso
	- virtualbox 7.0.8
	- packer 1.9.1
	- guestfs-tools	
	-ansible 2.10.8
           config file = None
           configured module search path = ['/home/n/.ansible/plugins/modules', '/usr/share/ansible/plugins/modules']
           ansible python module location = /usr/lib/python3/dist-packages/ansible
           executable location = /usr/bin/ansible
           python version = 3.10.6 (main, May 29 2023, 11:10:38) [GCC 11.3.0]
	- OpenSSH_8.9p1 Ubuntu-3ubuntu0.1, OpenSSL 3.0.2 15 Mar 2022
        - Vagrant 2.3.7

	- etc/ssh/ssh_config.d/10-PubkeyAcceptedKeyTypes-ssh-rsa.conf:

Host *
    HostkeyAlgorithms +ssh-rsa
    PubkeyAcceptedKeyTypes +ssh-rsa

