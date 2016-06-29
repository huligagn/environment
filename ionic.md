#安装nodejs

访问官网，参看如何安装

#安装cordova和ionic

```

npm install -g cordova

npm install -g ionic

```

如果出现长时间不能安装，可以换npm的镜像，我使用的是淘宝镜像，切换镜像有以下三种方式，建议使用第三种。

```

## method 1 通过config配置

npm config set registry https://registry.npm.taobao.org 

npm info underscore 

# 如果上面配置正确这个命令会有字符串response



## method 2 命令行指定

npm --registry https://registry.npm.taobao.org info underscore



## method 3 写入 .npmrc 文件

nano .npmrc

# 写入 registry = https://registry.npm.taobao.org

# 保存退出

```

#新建工程

```

ionic start project_name tabs

# 使用tabs作为工程框架，也可以使用blank（从零开始）、sidemenu（侧边栏工程）

```



#测试工程

```

cd project_name

ionic serve

```



#编译工程

- 进入工程目录添加platform

```

ionic platform add android

```

- 执行编译

```

ionic build
# android sdk needed here

```