AlmaLinux 9.x 安装mongo 7.x 的一个bug
https://www.mongodb.com/community/forums/t/openssl-error-when-starting-mongosh/243323/3

dnf remove mongodb-mongosh

dnf remove mongodb-mongosh
dnf install mongodb-mongosh-shared-openssl3
dnf install mongodb-mongosh
需要先卸载mogno 安装mongosh 再安装mongo
dnf install mongodb-org -y
