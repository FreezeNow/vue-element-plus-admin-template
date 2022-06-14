# element-plus-admin-template

> 这是一个极简的 vue admin 管理后台。它只包含了 Element UI & axios & iconfont & permission control & lint，这些搭建后台必要的东西。

[线上地址](https://freezenow.github.io/vue-element-plus-admin-template/)

该项目以[vue-admin-template](https://github.com/PanJiaChen/vue-admin-template/)为基础，使用 `vue-cli 5 + Vue 3 + Element Plus` 进行构建。使用`prettierrc`为格式化工具，并注释了原有的部分`eslint`规则，如有需要，请自行修改。

## Build Setup

```bash
# 克隆项目
git clone https://github.com/FreezeNow/vue-element-plus-admin-template.git

# 进入项目目录
cd vue-element-plus-admin-template

# 安装依赖
npm install

# 建议不要直接使用 cnpm 安装以来，会有各种诡异的 bug。可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run dev
```

浏览器访问 [http://localhost:9528](http://localhost:9528)

## 发布

```bash
# 构建测试环境
npm run build:stage

# 构建生产环境
npm run build:prod
```

## 其它

```bash
# 预览发布环境效果
npm run preview

# 预览发布环境效果 + 静态资源分析
npm run preview -- --report

# 代码格式检查
npm run lint

# 代码格式检查并自动修复
npm run lint -- --fix
```

更多信息请参考 [使用文档](https://panjiachen.github.io/vue-element-admin-site/zh/)
