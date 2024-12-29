# EasyAI-uniapp-aigc

EasyAI小程序，将ComfyUI工作流进行封装，转为全平台应用，支持Android、iOS、H5、微信、支付宝、百度、字节跳动、快应用等平台。

## 界面截图
![](./github-desc.jpg)


## 功能
* 支持自定义工作流应用，支持文生图、图生图、文/图生视频
* 支持工作流转换为简易的操作界面，支持用户自定义界面及参数
* 接入支付
* 支持图片分享社区
* 支持多任务和实时任务状态
* 支持个人空间查看自己的绘图历史记录

## 使用方法

1. 下载项目代码
```bash
git clone https://github.com/bobvinch/easyai-uniapp-aigc.git
```
2. 安装依赖
```bash
npm i
```
3. 运行项目
```bash
npm run dev:h5 
npm run dev:mp-weixin
npm run dev:mp-alipay
npm run dev:quickapp
```
4. 预览
H5预览：http://localhost:5173
微信预览：运行npm run dev:mp-weixin后，使用微信开发者工具打开终端提示的项目目录，导入微信开发者工具即可以预览

## 参与贡献
欢迎大家参与贡献EasyAI小程序，让AIGC落地更加简单。
### 提交代码
1. Fork本项目，并clone到本地
2. 在本地创建新的分支，进行开发
3. 提交代码到自己的fork仓库
4. 创建Pull Request到本项目
5. 等待合并
### 欢迎大家一起将项目做的更好