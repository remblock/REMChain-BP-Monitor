# REMChain-BP-Monitor

#### This script will monitor to see if the block producer is producing blocks within the specified timeframe, if the block producer fails to producer a block a telegram notifcation will be sent. The timeframe can be adjusted according to the block producers tolerance/preference.

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
