You may find something of interest here if you use the Korn Shell.

## Use in your scripts

Paste the following line in your ".profile":

```ksh
export FPATH=$FPATH:<Path to this directory>
```

Now in your script:

```ksh
#!/bin/ksh
capitalize hello world
```
