# Why should we use SSH with GitHub or anything else?


## SSH Keys & Github

### There are 2 methods to clone the repo
``` 
SSH and HTTPS
```
- We have 2 types of repos :
```
Public and Private
```

- Generate SSH keys on your local system
- Copy the key from local system to the specific repo on Github (ci-start-code)
- .ssh folder where we have SSH keys available
- Name the new key as your name e.g. ugne

1. ```ls -a``` in home dir
2. ``` cd.shh/```
3. ``` ls``` shows all the current keys 
4. ``` ssh-keygen -t rsa -b 4096 -C "uokmanaite@spartaglobal.com"```
5. ``` cat ugne.pub```
6. Copy the key
7. Go on github repo -settings -deploy keys - add deploy key
8. Paste the link and use same name 
9. Now the key is aded to Github
10. To change you would have to delete and add new one

### It is essential to write descriptive names e.g. ugne-jenkins
- knowing which keys to link with what 

