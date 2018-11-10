## Steps:
1. TYPE the following command in the console.

   (replacing *[proxy]* with your proxy and *[port]* with your port number)
 
 `$ export http_proxy="http://proxy:port"`

   (to check)
 
 `$ sudo apt-get update`


#### IF THIS DOES NOT WORK
2. Open **apt.conf** file in the following directory  **/etc/apt/**
  ```conf
   $ cd /etc/apt
   $ sudo vim apt.conf
   ```

  (this will create the apt.conf file if it does not exist)
3. Add the following line:
> Acquire::http::proxy "http://poxy:port/";


## ONLY works for apt-get
