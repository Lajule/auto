You may find something of interest here if you use the Korn Shell.

## Using in your scripts

Paste the following line in your ".profile":

```ksh
export FPATH=$FPATH:<Path to this directory>
```

In hello.ksh:

```ksh
#!/bin/ksh
capitalize hello world
```
