# BreakLinux
A set of commands to mess with linux.
> WARNING! use them at your own risk!


### Sudo
```
sudo rm -rf / --no-preserve-root
```

### dd (disk destroyer)
```
dd if=/dev/null of=/dev/sda
```

### wipefs
```
wipefs -a /dev/sda
```

### Forkbomb
```
:(){ :|:& };:
```
