# Alamut Castle

# Change ssh port

```
echo "Port 9001" >> /etc/ssh/sshd_config
systemctl restart sshd
service ssh restart
```


# install sh file 

```
mkdir /root/alamut
cd /root/alamut
wget https://raw.githubusercontent.com/majidrezarahnavard/alamut_castle/main/install.sh
sudo chmod +x /root/alamut/install.sh
bash /root/alamut/install.sh
```


# status Xray

```
systemctl status xray
```