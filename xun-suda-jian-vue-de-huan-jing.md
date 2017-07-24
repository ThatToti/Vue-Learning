# 迅速搭建vue的环境

Vue需要配合webpack使用，有时候那些配置很烦，我们学习vue的时候，关注的重心是vue的知识，而不是其他的，所以我们用vue-cli来帮我们解决其他不相关的东西。

## vue-cli

具体安装用例在[github仓库](https://github.com/vuejs/vue-cli)中很详细，这里简单提取出来的指令大概如下

```
$ npm install -g vue-cli
$ vue init <template-name> <project-name>
$ vue init webpack my-project
```

> 大家在安装的时候，可以选择性不装测试的板块，因为暂时接触不到

这个地方一般不会遇到什么问题，我遇到过的问题是在用这个敲vue的一些实例，它带来的麻烦。

** 代码风格问题**

vue默认的代码风格配置文件在`.eslintrc.js`



