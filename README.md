# REMChain-BP-Monitor

#### This script monitors to see whether a producer has produced blocks within a specified period, it can also be used to monitor for any missed swap or oracle actions. Additionally, it can check for a remcli response and check the usage of the server RAM & Disk space. In the event the script detects an issue, a notification will be sent via telegram.
 
***

### Setup REMChain-BP-Monitor:

```
sudo wget https://github.com/remblock/REMChain-BP-Monitor/raw/master/remchain-bp-monitor && sudo chmod u+x remchain-bp-monitor && sudo ./remchain-bp-monitor
```

***

### Setup Testchain-BP-Monitor:

```
sudo wget https://github.com/remblock/REMChain-BP-Monitor/raw/master/testchain-bp-monitor && sudo chmod u+x testchain-bp-monitor && sudo ./testchain-bp-monitor
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
