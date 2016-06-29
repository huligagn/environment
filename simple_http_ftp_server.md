#搭建简单http服务器
```
python -m SimpleHTTPServer 80
```
#搭建简单ftp服务器
##step1
```
pip install pyftpdlib
```
sometimes it needs to be executed with sudo
##step2
```
python -m pyftpdlib -p 21
```
sometimes it needs to be executed with sudo, too.
# pip problem
```
sudo apt-get install python-dev libatlas-base-dev gfortran
pip install --upgrade pip
```