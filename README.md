# NodeRED on Raspberry Pi

### 1. Installation

In terminal, type the following command:
```
bash <(curl -sL https://raw.githubusercontent.com/node-red/linux-installers/master/deb/update-nodejs-and-nodered)
```
This should take about 20-30 minutes, depending on the speed of the Raspberry Pi. Reference: https://nodered.org/docs/getting-started/raspberrypi

### 2. Run Node-RED

To run Node-RED:
```
node-red-start
```

To stop Node-RED:
```
node-red-stop
```

To restart Node-RED:
```
node-red-restart
```

To view log:
```
node-red-log
```

### 3. Remote SSH from Mac OS

Let us first determine the Raspberry Pi's IP address by typing the following command in the terminal of your Raspberry Pi: 
```
hostname -I
```

On your Mac, in the terminal type:
```
ssh pi@<your Rapberry PI's IP address without the bracket>
```
You will be asked for the Raspberry Pi's password. See below:

![SSH](https://raw.githubusercontent.com/mpipatta/NodeRED/master/images/SSHpi.png)


