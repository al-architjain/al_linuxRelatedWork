### TYPE THE FOLLOWING IN KONSOLE
(replacing proxy with your proxy and port with your port number)
* `export http_proxy="http://proxy:port"`
to check
* `sudo apt-get update`

## if does not work
## add this to /etc/apt/apt.conf 
(create apt.conf if does not exist)
> Acquire::http::proxy "http://poxy:port/";

## ONLY for apt-get
