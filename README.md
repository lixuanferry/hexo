# 搭建Hexo博客

## 1. 安装并配置git

`$ git config --global user.email "you@example.com"`

`$ git config --global user.name "Your Name"`

## 2. 安装Node.js
## 3. 安装cnpm
`npm install -g cnpm --registry=https://registry.npm.taobao.org`
## 4. 安装hexo
`cnpm install -g hexo-cli`
## 5. 初始化hexo
###### 新建一个空文件夹blog

`cd blog`

`hexo init`

## 6. 启动hexo
`hexo s`
## 7. 写文章
`hexo n "article_title"`
## 8. 生成
`hexo g`
## 9. 部署到github
###### Create a new repository
###### Repository name: yourname.github.io
## 10. 安装hexo插件
`cnpm install --save hexo-deployer-git`
## 11. 修改_config.yml文件
###### deploy:
###### &emsp;type: git
###### &emsp;repo: //仓库地址
###### &emsp;branch: master
## 12. 部署到远端
`hexo d`
