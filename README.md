# smtq-manifest

## Install repo
```
sudo apt update
sudo apt install repo
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
repo init -u git@github.com:ark-linux/smtq-manifest.git -b master -m develop.xml
```

## Repo sync
```
repo sync -j5
```
## Checkout branch
Checkout branch before you modify
```git checkout master```

## Check repo status
```repo status```

