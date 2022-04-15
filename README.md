# GitKraken
用于破解GitKraken-6.5.2至PRO版！

# 历史版本下载
（改改版本号就行）

+ Linux-deb : https://release.axocdn.com/linux/GitKraken-v6.5.2.deb
+ Linux-rpm : https://release.axocdn.com/linux/GitKraken-v6.5.2.rpm
+ Linux-tar.gz : https://release.axocdn.com/linux/GitKraken-v6.5.2.tar.gz
+ Win64 https://release.axocdn.com/win64/GitKrakenSetup-6.5.2.exe
+ Mac : https://release.axocdn.com/darwin/GitKraken-v6.5.2.zip

# Patch
```
git clone https://github.com/LYcongtou/GitKraken.git
cd GitKraken/GitKraken
yarn install
yarn build
```

# Windows
```
node dist/bin/gitcracken.js patcher --asar C:\Users\Administrator\AppData\Local\gitkraken\app-6.5.2\resources/app.asar
```

# Mac
```
node dist/bin/gitcracken.js patcher --asar 你的gitkraken的目录/resources/app.asar
```


最后重新启动GitKraken....直至右下角PRO
