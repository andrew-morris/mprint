mprint
======

## Summary

A stupid python class I wrote that doesn't even really save that much time

## Usage

Import the mprint method of the morris class
```
>>> from morris import mprint
```

Give a console update
```
>>> mprint.update("This is an update")
[+] This is an update
```

Give a console error
```
>>> mprint.error("This is an error")
[X] This is an error
```

Give an important message
```
>>> mprint.important("This is a important")
[!] This is a important
```
