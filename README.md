# 前端代码流程模版

## 备注

```
该模版为前端代码流程模版
包含项目所需要的基础目录结构、基础的依赖、和一些格式化代码的工具
```

## 功能列表

- [x] less/sass
- [x] ES6
- [x] element-ui（按需加载）
- [x] vue-router
- [x] vuex
- [x] axios
- [x] iconfont
- [x] loadsh
- [x] mockjs

## 代码流程：

```
npm run lint
手动执行代码检查，匹配.eslintrc.js文件中的规则，并修改一些代码问题

prettier
保存的时候自动格式化代码，基于项目中的.prettierrc.js文件
编辑器需要安装prettier扩展

pre-commit && lint-staged
commit时候检查eslint语法，并按照.prettierrc.js修改
有问题会阻止提交
```

> 可以使用 git commit --no-verify (-n) 来绕过 pre-commit && lint-staged 这个环节
