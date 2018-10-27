#goto rtl8723be.conf file in etc/modeprobe.d/
#if it is not create one

### COMMANDS
'''conf
$ cd /etc/modprobe.d/
$ vim rtl8723be.conf
'''

## VIM FILE OPENS
# ADD the following line to rtl8723be.conf
'''conf
  options rtl8723be ant_sel=1
'''

#save
## VIM CLOSED
#reboot

#if it FAILS make ant_sel=2
