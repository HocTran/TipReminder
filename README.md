# TipReminder
A cool tip reminder collection


## GIT

#### to show the git commits with diff  of file
```
git log -p -- <file>
```

#### to show the ENTIRE history of a file (including CONTENT)
```
git log --follow -p -- <file>
```

## CMD

#### to copy the key to the ssh-server
- Require enable 'Remote Login' from 'Sharing' in the server device (Mac OS setting).
```
cat ~/.ssh/id_rsa.pub| ssh <user>@<ip address> 'cat >> ~/.ssh/authorized_keys'
```
