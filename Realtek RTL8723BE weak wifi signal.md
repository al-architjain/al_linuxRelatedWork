## Steps:
1. Open **rtl8723be.conf** file in **etc/modeprobe.d/**.
    (if it does not exists, then create it.)
    ##### COMMANDS
    ```conf
    $ cd /etc/modprobe.d/
    $ vim rtl8723be.conf
    ```
    *{ VIM FILE OPENS }*

3. Add the following line into **rtl8723be.conf** file.
    ##### Type
    ```conf
      options rtl8723be ant_sel=1
    ```

4. save
    *{ VIM CLOSED }*
5. reboot
6. if it FAILS, change *ant_sel=2* and **reboot**
