# webstack
网站导航（**用来记录自己常用的网站**）
>所使用的主题网站（通过修改config.yml文件中`theme`字段的值来确认使用哪个主题）：
> 
> https://webstack.hclonely.com（导航网站）

**启动步骤：**
```shell
npm install hexo-cli -g

hexo init blog

cd blog

npm install

hexo server
```

**部署到编译过的文件到GitHub Pages**

部署到的是ghostasoul.github.io项目中的webstack分支，main分支存储的是源文件
```shell
hexo clean && hexo deploy
```

> *页面访问地址:* `https://ghostasoul.github.io`