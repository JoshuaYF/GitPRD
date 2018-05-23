# 基于GIT的产品原型(PRD)管理

## 客户端
* mac app免安装
* 内嵌web view, 使用html,js,css写页面
* 自动安装配置本地git环境 (通过一个url地址加载配置)
* 使用同一个git账号, 使用人员不需要额外注册账号.
* 分支列表
* 新建分支
* 点击在Finder里打开本地文件夹
* 点击浏览器打开本地PRD
* 点击浏览器打开在线PRD
* 更新提醒
* 点击拉取更新
* 本地改动提醒
* 提交改动 (需要填写备注, 显示更新的文件列表, 电脑登录的用户名要写到备注开头里)
* 撤销改动
* 更新历史
* 更新历史-点击在Finder里打开本地文件夹
* 更新历史-点击浏览器打开本地PRD
* 更新历史-点击浏览器打开在线PRD
  
## 服务端
* Web服务器
* Url里内嵌分支名
* Url里内嵌commit id
* 注册git hook自动拉取更新
