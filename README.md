## Links
- Homepage and documentation
  - Link to: https://github.com/dyangjs/dyang-cli
- Logs
  - Link to: https://github.com/dyangjs/dyang-cli/blob/master/logs.md
  
## Install
```shell
npm i dyang-cli -g
```
## Quick Start （初始化脚手架安装项目依赖）
```shell
dyang -m
```

## 注意事项
```shell
Mac系统可能会存在权限问题，您可以授权npm全局安装目录:sudo chmod -R 777 全局安装目录;
目录查看：执行npm config list 找到prefix
```

## 功能列表
```shell
a) 支持项目代码<% example %>导出
b) 个性化创建项目
c) 第三方资源管理
d) Vue-router配置自动生成
e) 系统化处理webpack开发配置
f) 开发阶段包资源共享
```

## Options
```shell
-c, --create     Create a new project
-v, --version    Show current version
-s, --start      Run dev server
-b, --build      Build the project
-i, --install    Install package resources:-i vue@2.0.0.0 or -i vue
-w, --whitelist  Show the packages that are allowed
-t, --translate  Export Project <% example %>
-l, --lang       Show Translate Support Langs
-r, --repair     Repair Project Files
-u, --upgrade    Upgrade the common UI component library
-m, --mending    Initialization the CLI
-h, --help       output usage information
```