### 项目目录

```
web-demo //项目名称
    |__ public //项目打包目录
    |    |__ favicon.ico //项目浏览器icon
    |    |__ index.html //vue入口的html文件
    |__ src //项目业务代码目录
    |    |__ assets //项目静态文件目录
    |    |    |__ icons //项目字体库
    |    |    |__ imgs //存放项目所有的图片及svg文件
    |    |    |__ scss //存放项目公共scss文件、css文件、element-ui.scss等公共样式表
    |    |__ components //项目组件库
    |    |__ config // 项目环境总配置文件
    |    |    |__ index.js //存放所有的配置字段
    |    |__ data //项目从后端获取数据层
    |    |    |__ index.js //封装请求的公共类，所有请求模块都必须引入这个公共类
    |    |    |__ modules //存放所有请求类
    |    |__ plugins //外部引入组件配置
    |    |__ router //项目路由管理
    |    |    |__ index.js //初始化加载所有的路由，并设置全局首位等有关路由的设置
    |    |    |__ modules //存放所有模块的路由
    |    |__ store //全局状态管理
    |    |    |__ index.js //动态初始化所有模块的状态管理
    |    |__ utils //项目工具类
    |    |__ views //存放项目的所有界面(.vue文件，后续可能改为pages)
    |    |__ App.vue //项目入口vue文件
    |    |__ main.js //项目入口js文件
    |__ .env.development----项目开发环境配置文件
    |__ .env.production--------项目生产环境配置文件
    |__ .env.test-------------------项目本地测试环境配置文件
    |__ .gitignore-----------------Git提交忽略目录
    |__ babel.config.js---------babel配置文件
    |__ package.json-----------webpack配置目录
    |__ vue.config.js------------VUE配置目录
```



