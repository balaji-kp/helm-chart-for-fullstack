$ sudo systemctl stop kubelet
$ sudo systemctl start kubelet
$ strace -eopenat kubectl version
