# Bandit Level 15 to 16 Writeup


Author: [Aryan Sharma](https://github.com/Aryans-20)

Problem Page: [bandit11](https://overthewire.org/wargames/bandit/bandit16.html)

## List of Commands Used
```
openssl:a toolkit for ssl related commands
s_client:implements an ssl client to connect to a remote host via a given port.
```

## Walkthrough
Read about all the commands required to solve the level. Used echo to feed password but it did not work.
So later I had to fill in the password manually. Could not automate the process of entering password.
## Password
`cluFn7wTiGryunymYOu4RcffSxQluehd`

## Bash/Python script to automate the process
"#! /bin/bash"
"openssl s_client -connect localhost:30001"
