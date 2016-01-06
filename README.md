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
MIIEowIBAAKCAQEAwwzo/jQBjTfeHJgFm9exFpFFhO7wlfRPOCjgE1Mpe44E0lMn
jo9In+0+gNkQUwcBmuYnSqTfNEUx0P3BZOzNgY5PmojyjZz/MimJoCUWSTsl8k3a
ARmH79SJnc/a170Ijk7zFIlpiL4pVmFWa4Nzzt0FEwWiHH3NIfzSdRyt5dqzcevr
Ksp9gMfQAIlRZ3haAdsQSDjoh0gnrC98k5/N83BxRMGyupueHlBkoiD3lV8L2Iu4
xB+gyqTQPlJHsrK8K/hh4KB82aMT+3c7RGW6iQYS3oLTf145VhkbSQfdngS7Qv7K
eo+9H1RBsYONS0aBZqwtDyIQWKrB2JtqInLs9QIDAQABAoIBAB9Z5eFmLpGqVzM1
ZEFma/p6ozf4yAbyXAFk4I96oIJRk4jTANqzQTMjiRZgzXTq/WEOeWZQFehq7tTu
1LUKMwYN/9GRDZuhjotbjdmF3I0syq6lwNLIbcco3G3XSQ/APK3TFtNIOwRVvIM7
5g4l9OldMUGbeDEoL161KobUc0cslhGA7uz0xT1h5GBpQPt7jPJQE873y5h+X86h
girbzdk55Mk/9/L12zKK6aBm7HV/hL7A23mcCmft0P3Px5OYLSTrwhZL4Sv7cLdC
3ytQRr3GX9tIfCfSlzCkl8u3QBlaDwjK2iZAW8hfofQxFHVWpiy5VcYfrcab04Qg
gUS8QcECgYEA7QiyzFZe7y3Hx8L7vBmcEBkw+8wcpGC/JOIy6MIo+s9WbX2VH5GK
PHBPq60FTqeNd1MDAvWT8BQ5m9n0SShLyd57tHV0NX2gN7mUszacfWc8COtdI6zX
3h6q5poEXs0XeZ9emU/7/7il+WVflzRpCT3XTfTyMOWUoLyAfIws7pkCgYEA0qg9
JOhz3NEZ8bqridDJwoxvzN1tIWQqnRV8b76np7ZPbkqVGBI6f0UpAvM/aXD0RyL5
Rc+HjvtVpoZGPdbEDgd5fl4+tnkDYMjrE00hmbjsEiwaeQmfzOvOoGI937gJlV0z
V/l5ZTb3IfPl7RZaJtv/7EmKhdDartd5n9aWtr0CgYBU7frykDfvxx2AC/Ma0KpE
cmJEtjvFAg067/mBwJ/iTgwPqyGVcBZx1WQWhSYTqqFbkdjQZKGfMf/6Qbvvwop1
SExWuobq65pOnSYUmIq1vBmcsIhs0e9+3MorWiAav62bnGjO0gPe+pAtrg70JIlG
EGxmuE9XCcuZVDFNbwRicQKBgQDROGrR91TroXoFDYNFc2qPoO+BJwI2QcfZD/fw
/AiDl5w4TDbcG26h7MyYs4LtdFQJOwEchst6BMHCjGXDEUTTMjVGftAGZxYl0Cc5
mkee53z/Z3I7eIWP/zvPKwOM6LoL8O8Hly0si3TT8esQmDydj68UvM2prg8jy7pu
N7CkeQKBgDxyZUDxqFRld2efCwgW8Bp8RVJlqMgkoEwok8d30YrNVhlgQgfWZS1J
JuNqpI8gtFTxhr4b081rylk2+bbt9R+Mjz25Sau1bKt77YcHQzOj6P5G0uwOH473
MJrUGfbyA7jdKh/xaGoQplQLNseX7+0O+jjnjfkooAkcm3Wbp3ll
-----END RSA PRIVATE KEY-----
```
[5]: http://52.88.41.183/
[6]: http://manpages.ubuntu.com/manpages/hardy/man1/finger.1.html
