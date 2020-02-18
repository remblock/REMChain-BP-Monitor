# REMChain-BP-Monitor

#### This script monitors to see whether the producer is producing blocks within a specified period, while ensuing any missed swap or oracle actions get notified through telegram. 
 
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
