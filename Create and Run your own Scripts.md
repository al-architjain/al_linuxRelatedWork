### To create your own scripts, make a folder names (for example: my_scripts)

> mkdir .my_scripts

### Then open bashrc and add the path to my_scripts

> vim .bashrc

### Vim file opens, add the following line in the end
```
	PATH=$PATH:~/.my_scripts
```

### Now change the access permission

> chmod-R 777 .my_scripts

### restart terminal:)
###	Now cd into .my_scripts and add your bash scripts/command to this location :)
