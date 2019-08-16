- 安装ssh

sudo apt install openssh-server

- 启动

sudo service ssh start

- 常用命令：

添加ssh pub key

ssh-copy-id -i .ssh/id_rsa.pub ethanold@192.168.7.105 

登录

ssh ethan@192.168.7.103

scp test ethan@192.168.7.103:~/

scp -r ethan@192.168.7.103:~/test test

