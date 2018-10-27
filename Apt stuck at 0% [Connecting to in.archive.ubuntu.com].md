## Apt stuck at 0% [Connecting to in.archive.ubuntu.com]

### To solve do the following
#### 1. Goto gai.conf file in /etc/ as super user

 ```bash
$ sudo vim /etc/gai.conf
```

#### 2. uncomment line *54*

```conf
> precedence ::ffff:0:0/96  100
```

to

*```conf
> //precedence ::ffff:0:0/96  100
```*

#### 3. save and exit
