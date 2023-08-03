[RedHat]
rocky-server ansible_host= 192.168.56.110

[Ubuntu]
ubuntu-server ansible_host= 192.168.56.20

[linux:children]
RedHat
Ubuntu