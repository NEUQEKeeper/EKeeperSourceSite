---
title: Hello World
cover: false
tags:
  - hello
categories:
  - hello
---
Welcome to [Hexo](https://hexo.io/)! This is your very first post. Check [documentation](https://hexo.io/docs/) for more info. If you get any problems when using Hexo, you can find the answer in [troubleshooting](https://hexo.io/docs/troubleshooting.html) or you can ask me on [GitHub](https://github.com/hexojs/hexo/issues).

## Installation

下载 nodejs、npm、cnpm

~~~bash
npm install -g cnpm --registry=https://registry.npm.taobao.org
~~~

下载 hexo

~~~bash
cnpm install -g hexo -cli
~~~

下载主题以及渲染器

~~~bash
git clone -b master https://gitee.com/immyw/hexo-theme-butterfly.git themes/butterfly

npm install hexo-renderer-pug hexo-renderer-stylus --save
~~~

下载 git 插件（用于部署）

~~~bash
cnpm install --save hexo-deployer-git
~~~

配置部署信息（_config.yml）

~~~yaml
deploy:
  type: git
  repo: https://github.com/NorthBoat/NorthBoat.github.io
  branch: master
~~~

## Quick Start

### Create a new post

``` bash
$ hexo new "My New Post"
```

More info: [Writing](https://hexo.io/docs/writing.html)

### Run server

``` bash
$ hexo server
```

More info: [Server](https://hexo.io/docs/server.html)

### Generate static files

``` bash
$ hexo generate
```

More info: [Generating](https://hexo.io/docs/generating.html)

### Deploy to remote sites

``` bash
$ hexo deploy
```

More info: [Deployment](https://hexo.io/docs/one-command-deployment.html)

