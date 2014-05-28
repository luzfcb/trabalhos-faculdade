trabalhos-faculdade
===================


# Configurando Servidor FTP Seguro em Linux




Instalar Xubuntu 14.04 64bits

Servidor: 107.170.216.161



```bash
apt-get install ssh
apt-get install vsftpd
useradd -m user1 -p user1
useradd -m user2 -p user2


service vsftpd stop
service vsftpd start
```





## Referências


https://help.ubuntu.com/community/vsftpd

https://www.digitalocean.com/community/articles/how-to-set-up-vsftpd-on-ubuntu-12-04

https://www.digitalocean.com/community/articles/how-to-configure-vsftpd-to-use-ssl-tls-on-an-ubuntu-vps

http://www.claudioborges.org/tutoriais/_vsftpd.html
