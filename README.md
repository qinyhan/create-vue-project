# create-vue-project
创建VUE脚手架命令步骤

# VUE使用命令  

## 1. 切换源为 taobao 源
$ npm set registry https://registry.npm.taobao.org/

## 2. 全局安装 vue-cli 一般是要 sudo 权限的
$ npm install --global vue-cli

## 3. 全局安装 apicloud-cli
$ npm install --global apicloud-cli

## 4. 创建一个基于 vue 模板的项目
$ vue init webpack my-project
                   项目名称
          
## 5. 安装依赖包

$ cd my-project
$ npm install
$ npm run start

## 6. 打包构建

$ npm run package


# yarn使用命令

## 1.安装yarn
$ npm install -g yarn 或 install yarn

## 2.查看yarn版本
$ yarn version

## 3.初始化一个新项目
$ yarn init

## 4.添加依赖包

$ yarn add [package]
$ yarn add [package]@[version]
$ yarn add [package]@[tag]

## 5.升级依赖包
$ yarn upgrade [package]
$ yarn upgrade [package]@[version]
$ yarn upgrade [package]@[tag]

## 6.移除依赖包

$ yarn remove [package]

## 7.全局安装vue脚手架
$ npm install -g vue-cli

## 8.创建一个基于 webpack 模板的新项目
$ vue init webpack Vue-youzan


# VUE + ApiCloud使用命令  
##安装apicloud-cli  
$ npm install apicloud -g



