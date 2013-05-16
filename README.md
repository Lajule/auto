You may find something of interest here if you use the Korn Shell.

## Contents

`bye`: Normal termination.  
`capitalize`: Capitalizes the given string.  
`die`: Anormal termination.  
`dos2unix`: Converts a dos file to a unix one.  
`index`: Prints the position (form the beginning) of given character in given string.  
`lock`: Returns 1 if a previous instance is running, otherwise returns 0.  
`unlock`: Releases lock for others instances.  
`log`: Inserts a new entry in log file.  
`mktmpf`: Returns a new temporary file name.  
`pad`: Right pads the given string with given character.  
`prompt`: Sets a pretty prompt.  
`push`: Pushes a value into a stack.  
`pop`: Pops the first value from a stack.  
`size`: Gets the number of elements in a stack.  
`quote`: Quotes the given string.  
`readkey`: Reads a key and stores the result in given variable name.  
`readline`: Reads a line and stores the result in given variable name.  
`rindex`: Prints the position (form the end) of given character in given string.  
`rpad`: Left pads the given string with given character.  
`rsub`: Replaces the last occurence of given pattern.  
`sub`: Replaces the first occurence of given pattern.  
`tabify`: Converts spaces into tabs.  
`unix2dos`: Converts a unix file to a DOS one.  
`untabify`: Converts tabs into spaces.  

## Using in your script

Paste the following line in your ".profile":

```ksh
export FPATH=$FPATH:<Path to this directory>
```

In "hello.ksh":

```ksh
#!/bin/ksh
bye "hello world !"
```
