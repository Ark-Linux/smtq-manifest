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
repo sync -j5
```
## Checkout branch
Checkout branch before you modify
```git checkout master```

Path of repos
- qcs-adk-non-hlos-1-2: ./QCS40X_WS
- qcs-adk-hlos-1-2: ./QCS40X_WS/LE.UM.4.1.2
- qcs-adk-kernel-1-2: ./QCS40X_WS/LE.UM.4.1.2/apps_proc/kernel
- meta-sdk: ./QCS40X_WS/LE.UM.4.1.2/apps_proc/poky/meta-sdk
- meta-ark: ./QCS40X_WS/LE.UM.4.1.2/apps_proc/poky/meta-ark

