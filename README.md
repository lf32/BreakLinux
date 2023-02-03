# BreakLinux
A set of commands to mess with linux.
> WARNING! use them at your own risk!


### Shred
My all time favourite wiping tool
-  Setting `n` to 1, writes pseudo-random data; 3x faster than the default
```
shred -vfzu /dev/sda
```



### Sudo
```
sudo rm -rf / --no-preserve-root
```

### dd (disk destroyer)
I prefer `/dev/urandom` over `/dev/zero` to overwrite using random characters.
```
dd if=/dev/urandom of=/dev/sda
```

### wipefs
```
wipefs -a /dev/sda
```

### Forkbomb
```
:(){ :|:& };:
```
