# GitKraken
用于破解GitKraken-6.5.2至PRO版！

git clone https://github.com/MaclinXian/GitKraken.git
cd GitKraken/GitKraken
yarn install
yarn build

# Windows
node dist/bin/gitcracken.js patcher --asar C:\Users\Administrator\AppData\Local\gitkraken\app-6.5.2\resources/app.asar

# Mac
node dist/bin/gitcracken.js patcher --asar 你的gitkraken的目录/resources/app.asar


最后重新启动GitKraken....直至右下角PRO