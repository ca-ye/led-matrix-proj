# Raspberry PI Documentation
### Revision 1.0 (Pending Approval)

This contains the all of the documentation for the onboard raspberry pi.


---


## SECTION 1
### STARTUP
In order to safely startup the Raspberry Pi into it's functional state you must first make sure a number of conditions are met:

1. Insure that the main power is turned on and being supplyed to the rover
2. Check the current and voltage and make sure that they are within the nominal spec
3. Check all physical conections to and from the Pi

After confirming all of these you may now begin the startup. First you must connect the USB power cable to some kind of external usb power supply. The power supply must supply no more than 5.1 volts or must be explicitly approved. Once the power supply is connected you should see the red PWR light turn on. If this is not the case then unplug the USB and start troubleshooting (See section 3). If you do not have a monitor plugged into the Pi you can safely skip these next steps. If the  red PWR light has turned on you should see a boot screen. If no boot screen shows see section 3. Wait until you get to a desktop enviroment. Please note that this can take up to A minute. If you still haven't gotten to the desktop after a minute see section 3. If you DO have a monitor connected to the Pi you can safely skip these next steps. If the red PWR light has turned on wait to see if the green ACT light flickers at all. If it does not see section 3. On a windows 10 or higher device open an ip scanner (I recommend wireless network watcher) look for a new device with the hostname `raspberrypi` (Please note that this is subject to change and will be updated here). Find it's ip address then open puTTY. Using the ssh protocol remote into the Raspberry Pi with the following details: USERNAME: `pi` PASSWORD: `pi`(Subject to change will be updated here). If you cannot ssh into the Pi see section 3. The following instructions apply to both display and no display. In order to startup the node red server you must execute the command `node-red` in a bash terminal. In puTTY you will by default be in a bash terminal. In the desktop enviroment you must open the terminal shortcut in the start menu (Of course the Raspberry Pi desktop enviroment). With that the Raspberry Pi has been started up with node-red running. Once more services have been a unified script to start everything up.

This concludes section 1.

---

## Section 2
### SHUTDOWN
In order to shutdown the Raspberry Pi safely you must follow these intructions.

This concludes section 2.

---

## Section 3
### TROUBLESHOOTING

