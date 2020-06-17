### 项目目录

```
web-demo //项目名称
    |__ public //项目打包目录
    |    |__ favicon.ico //项目浏览器icon
    |    |__ index.html //vue入口的html文件
    |__ src //项目业务代码目录
    |    |__ config //项目环境总配置文件
    |    |    |__ index.js //存放所有的配置字段
    |    |__ data //项目从后端获取数据层
    |    |    |__ index.js //封装请求的公共类，所有请求模块都必须引入这个公共类
    |    |    |__ modules //存放所有请求类
    |    |__ utils //项目工具类
    |__ static //存放应用引用静态资源（如图片、视频等）的目录，注意：静态资源只能存放于此
    |__ main.js //Vue初始化入口文件
    |__ App.vue //应用配置，用来配置App全局样式以及监听
    |__ manifest.json //配置应用名称、appid、logo、版本等打包信息
    |__ pages.json //配置页面路由、导航条、选项卡等页面类信息
```



