# LockScreenService

## What do?

permitt to lock the screen automatically when the system is suspended or hibernated;

## Install

clone the project ,

edit lockscreenservice.service changing  USER to your actual user,

move lockscreenservice.service to /etc/systemd/system ,

move scripts folder to your home ,

edit lock.sh for work with your lockscreen,(i use betterlockscreen that is based on i3lock so it is the default ,you can find it in aur or on [GitHub - pavanjadhaw/betterlockscreen: 🍀 sweet looking lockscreen for linux system](https://github.com/pavanjadhaw/betterlockscreen),)

chmod 777 lock.sh 

in the end to make the service work 

```bash
sudo systemctl start lockscreenservice.service
sudo systemctl enable lockscreenservice.service

              
```
