## Steps:
1. goto rtl8723be.conf file in etc/modeprobe.d/
2. if it is not create one in etc/modeporbe.d

    ###### COMMANDS
    ```conf
    $ cd /etc/modprobe.d/
    $ vim rtl8723be.conf
    ```
*{ VIM FILE OPENS }*

3. ADD the following line to rtl8723be.conf
    ```conf
      options rtl8723be ant_sel=1
    ```

4. save
*{ VIM CLOSED }*
5. reboot
6. if it FAILS, change ant_sel=2 and reboot
