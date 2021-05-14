# Bandit Level 9 to 10 Writeup


Author: [Aryan Sharma](https://github.com/Aryans-20)

Problem Page: [bandit11](https://overthewire.org/wargames/bandit/bandit10.html) 

## List of Commands Used
```
strings-prints all the human readable strings in a file.
grep-used to find specific strings in the text.
```

## Walkthrough
Read about all the commands required to solve the level. Initially I only used "strings data.txt" and it gave a lot of strings so I piped the results of strings to grep = and it worked 

## Password
`truKLdjsbJ5g7yyJ2X2R0o3a5HQJFuLk`

## Bash/Python script to automate the process
```
#! /bin/bash"
strings data.txt | grep "&=" 

```
