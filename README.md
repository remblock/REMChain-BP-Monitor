# REMChain-BP-Monitor

#### This script monitors to see whether a producer is producing blocks within a specified period, it can also monitor for any missed swap or oracle actions, check for a remcli responce and check the usage of the server RAM and Disk space. Once the script detects a problem a telegram notifcation will be sent.
 
***

### Setup BP-Monitor:

```
sudo wget https://github.com/remblock/REMChain-BP-Monitor/raw/master/remchain-bp-monitor && sudo chmod u+x remchain-bp-monitor && sudo ./remchain-bp-monitor
```

***

### Edit BP-Monitor Config:

```
nano remblock/remchain-bp-monitor/config
```

### Edit BP-Monitor (Enable/Disable):

```
nano /root/check-bp-monitor
```

#### Edit file to "on" to enable and "off" to disable
