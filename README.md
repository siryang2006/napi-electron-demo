# napi-electron-demo
# run step

#step1
:npm install

#step2
:npm start





# 其他
pip install setuptools

npm install -g node-gyp

npm i node-addon-api



# 单独编译
node-gyp rebuild

node-gyp rebuild --arch=x64

# 运行 electron
electron .


# 如果只想要napi的demo

##(1)拷贝文件

addon.cc和binding.gyp到test的文件夹

##(2)进入test文件夹

cd test

##(3)安装依赖

npm i node-addon-api

##(4)编译插件

node-gyp rebuild
