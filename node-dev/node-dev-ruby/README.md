# 大前端开发环境构建(含ruby)

构建本地前端的node-ruby开发环境，主要在ibbd/node-dev镜像的基础上，增加ruby，sass，compass等。

- Github:   https://github.com/ibbd/dockerfile-node/node-dev/node-dev-ruby 
- 镜像地址：https://hub.docker.com/r/ibbd/node-dev-ruby

## 基础说明 

- 基础镜像：ibbd/node-dev
- Ruby2.3.0
- RubyGems镜像使用淘宝的

## 已经安装的扩展

- sass 
- compass 

## 镜像 

- 从Dockerfile构建：`./build.sh`
- 从hub.docker.com获取：`docker pull ibbd/node-dev-ruby`

## 运行镜像

- `./run.sh`


