# smtq-manifest

## Install repo
```
sudo apt update
sudp apt install repo
```
## Change repo url if google is blocked
```
sudo vim /usr/bin/repo
```
Modify repo file
```
REPO_URL = 'https://aosp.tuna.tsinghua.edu.cn/git-repo'
```
## Repo init
```
repo init -u git@github.com:ark-linux/smtq-manifest.git -b master -m zepp-0.4.1.xml
```

## Repo sync
```
repo sync
```
