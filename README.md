killProcessOnPort
=================

Quickly kill a process that is hogging a port:

```
> killProcessOnPort 8000 -f
```

If you run it with no params, it will ask you for a port...

```
> killProcessOnPort
Which port do you want to stop the process on?
```

If you pass a port number it will tell you what is running on the port and ask for confirmation to kill it:

```
> killProcessOnPort 8000
Process on port is: node(44341)
Kill it? (Y/n)
```