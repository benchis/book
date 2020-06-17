### 项目目录

public----------------------项目打包目录

-----favicon.ico //项目浏览器icon

-----index.html //vue入口的html文件

src---------------------------项目业务代码目录

-----assets //项目静态文件目录

----------icons //项目字体库

----------imgs //存放项目所有的图片及svg文件

----------scss //存放项目公共scss文件、css文件、element-ui.scss等公共样式表

-----components //项目组件库

-----config // 项目环境总配置文件

----------index.js //存放所有的配置字段

-----data //项目从后端获取数据层

----------index.js //封装请求的公共类，所有请求模块都必须引入这个公共类

----------modules //存放所有请求类

-----plugins //外部引入组件配置

-----router //项目路由管理

----------index.js //初始化加载所有的路由，并设置全局首位等有关路由的设置

----------modules //存放所有模块的路由

-----store //全局状态管理

----------index.js //动态初始化所有模块的状态管理

-----utils //项目工具类

-----views //存放项目的所有界面\(.vue文件，后续可能改为pages\)

-----App.vue //项目入口vue文件

-----main.js //项目入口js文件

.env.development----项目开发环境配置文件

.env.production--------项目生产环境配置文件

.env.test-------------------项目本地测试环境配置文件

.gitignore-----------------Git提交忽略目录

babel.config.js---------babel配置文件

package.json-----------webpack配置目录

vue.config.js------------VUE配置目录

