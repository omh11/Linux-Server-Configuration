Linux Server Confguration for the Udacity training course.

## IP Address
- 52.88.41.183

## SSH port
- 2200

## Hosted Application URL
- [http://52.88.41.183/][5]

## grader account password
- "grader"

## .bash_history log (Software Install Summary)
```
exit
sudo adduser grader
finger grader
cat /etc/apt/souce.list
cat /etc/apt/sources.list
sudo apt-get install finger
finger grader
exit
sudo ls /etc/sudoers.d
sudo cat /etc/passwd
exit
sudo ls /etc/sudoers.d
sudp apt-get update
sudo apt-get update
sudo apt-get upgrade
gpasswd -a grader sudo
vi /etc/ssh/sshd_config
nano /etc/ssh/sshd_config
vi /etc/ssh/sshd_config
sudo ufw allow 2200/ssh
sudo ufw allow 2200/tcp
service ssh restart
sudo ufw allow 80/tcp
sudo ufw allow 123/tcp
sudo ufw show allowed
sudo ufw show added
sudo ufw enable
sudo dpkg-reconfigure tzdata
sudo apt-get update
sudo apt-get install ntp
sudo dpkg-reconfigure tzdata
sudo apt-get install apache2
ifconfig eth0 | grep inet | awk '{ print $2 }'
sudo apt-get install python-setuptools libapache2-mod-wsgi
sudo service apache2 restart
sudo apt-get install postgresql
pyhton
python
sudo nano /etc/postgresql/9.1/main/pg_hba.conf
cd /etc/postgresql/
ls
sudo nano /etc/postgresql/9.3/main/pg_hba.conf
cd..
cd~
cd ..
cd ~
sudo su - postgres
sudo apt-get install libapache2-mod-wsgi pyhon-dev
sudo apt-get install libapache2-mod-wsgi python-dev
sudo a2enmod wsgi
tail /var/log/apache2/error.log
sudo -u postgres createuser -s catalog
sudo -u postgres createuser -s $catalog
sudo -u postgres createuser -s $CATALOG
sudo -i -u postgres
sudo apt-get update
sudo apt-get install postgresql postgresql-contrib
sudo su - postgres
```

## Third Party Resources
- [finger][6]

## udacity_key.rsa Contents
```
-----BEGIN RSA PRIVATE KEY-----
MIIEpAIBAAKCAQEA3AQ2Uk2MfKHjlZGKj+8okvO0XqbzYBRfGzmISuuj1gvIm8Xp
uJz9Uu6wa9KlEgB8f2E5YWqBpHCO2blBDGrtOmFXfPMT27fyFK3BTjGoLj1jm04m
mRbmdR38mBMDDlCL2CXhQaZ7G8rahzrcg4dTCUMQqR6MQ/57/WVNN15hiDvJH7lB
tly2mDLCguVz+WCan/eSxRtXoqYO8rLuFDu72O/QISrKfOmn3xdT1RnjqpreUTRt
89B2gNA2g+QyZlvuHHezhSEdVz2iGYXCEOGWYicPD+7HoxT5+vhBZ9fdVPyzseR6
ivNUprCsNbKv7en050Vpp6SE9l9CktKNHFZnPwIDAQABAoIBADz0mcwxmgOJopD0
sqvv+ZDFHiq/HFx5KGRVizIemNSbjSfDLF6ud+y7Hnuw73TOV6++0vPvWx2g5aLi
lWgIU9NB1shSXCUakGI0RYMRdOPitC759u2hD5ZRCYNkeQtFO4lV7VOP+TmY+PRQ
VXnHSzUctIf2Y6wO3HE22K7HYkQosKFCbO81bTyqvWjQwWCkHh7+8Z1SjeQvXQee
7pkGzX13qHaR1gESCBfeLFMHi9Rc0wAWLGwzHRhRaLM7Qf/M9PMASyil+XKLzBUC
4rrBBMLPZaHC4FRxktglyYuKr2qqViTGzaP/mr7O/fkSrywjyh8sbf3dDJ79+CAN
NA4seEkCgYEA8+6YzZo88ZU7Uj+KyQpP7xvBPNcqcKiMqZVePNOKYIQkAvCvuW4M
iUGAz8l6YJ2oOWsPDzJmTCctlIUidoOgt1FU3xGKM1TfRYMeauvjXyhMS5JkoSJw
xE/b4cMPCIEeRgS+sAxg2rtZdYDPEY9mR0ifYC2bzCs5n+ALqNedTnUCgYEA5ua5
ad1n0xTRB/aRPkBTgPac1B0rzk6UCtHG6+DBgdi4fI12Bm21eF9vSftauUNyQFSR
nfFt3o+D93hHXQLSYfOum4ifqxrtELx8dvi5lmJcBO/VxwgxZTqldwP+UxE7dTth
rb+1DRwOqXzV2rPNHhNpJ3YvNLmvDyneXYt60GMCgYAV03uIqgxZ8Whla5oXcvzE
AE/CCd6aRfqQEfVkq+jtyeUO/ko65UXp4hqMfRKeIn0y5glq6q+MkNTbPS5gPFbd
EEHv07nx7d4schb+qiymDw0Elgy6/kHoztx1zuZBdIwo57PIPNNNvwW6JdRhVdto
9W6NRId0NUnqrDle2iwRIQKBgQDTPeABR0p2JUQ7ScuFLSp4AKZntCxgeSkdYN/g
6mV+WnwljvGcXgA4mO7iuy878MV0ryntWnQOujOcUpDPOgapEFv89RhGXMLnndks
qs53E5Nl/NkSVp+CIg5A/QlOi6Re0y3A3HNSBAox6wBnLjmIu29nZ8s2LG5IrCBA
apu4SwKBgQDm5SeOctSXyIqqZXpwfhPtQQna8Eba8nzQ8H3ihVZEbfAW3oW+xa1i
tlBQ7Bdf7zm1iKffMKFzS3vu+v9ZddbJkj25629h2cY3DK2EDt6ay6sweOsgEEhU
zbnDl7zDBzaB4J1jnhGyVCFMa8kb88nA17fg3Bb2CBKwXF+E+RcU4g==
-----END RSA PRIVATE KEY-----
```
[5]: http://52.88.41.183/
[6]: http://manpages.ubuntu.com/manpages/hardy/man1/finger.1.html
