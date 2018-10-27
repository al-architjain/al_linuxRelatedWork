## Python pip3 - cannot import name 'main' error after upgrading pip.md

### To recover the pip3 binary, degrade the pip version

```bash
$ sudo python3 -m pip uninstall pip && sudo apt install python3-pip --reinstall.
```
