## ⚡️ 简介

一个免费开源的中后台管理系统基础解决方案，基于 Vue3、TypeScript、Element-Plus、Pinia 和 Vite 等主流技术.

模板代码是从 [v3-admin](https://github.com/un-pany/v3-admin) 迁移而来，脚手架从 vue-cli 5.x 切换到了 vite 2.9.x，并作了一些繁琐的适配.

更推荐大家使用该 vite 版本！以后的重心也会从 [v3-admin](https://github.com/un-pany/v3-admin) 偏向本仓库.

## 特性

- **Vue3**：采用 Vue3 + script setup 最新的 Vue3 组合式 API
- **Element Plus**：Element UI 的正统续作
- **Pinia**: 传说中的 Vuex5
- **Vite**：真的很快
- **Vue Router**：没啥好说的
- **TypeScript**：JavaScript 语言的超集
- **PNPM**：更快速的，节省磁盘空间的包管理工具
- **Sass**：和 Element Plus 保持一致
- **Eslint**：代码校验
- **Pritter**：代码格式化
- **Axios**：没啥好说的，已封装好
- **注释**：各个配置项都写有尽可能详细的注释

## 功能

- **用户管理**：登录、登出演示
- **权限管理**：内置页面权限（动态路由）、指令权限、权限函数、路由守卫
- **多环境**：开发环境（development）、预发布环境（staging）、正式环境（production）
- **多主题**：内置普通、黑暗两种主题模式
- **错误页面**: 401、404
- **Dashboard**：根据不同用户显示不同的 Dashboard 页面
- **其他内置功能**：SVG、动态侧边栏、动态面包屑、标签页快捷导航、Screenfull 全屏、自适应收缩侧边栏（兼容移动端）

## 📚 文档

[简体中文](https://juejin.cn/post/7089377403717287972)

## 国内仓库

[Gitee](https://gitee.com/un-pany/v3-admin-vite)

## 预览

| 位置 | 账号 | 链接 |
| --- | --- | --- |
| github-pages | admin或editor | [链接](https://un-pany.github.io/v3-admin-vite) |

## 🚀 开发

```bash
# 配置
1. 安装 .vscode 中推荐的插件
3. node 版本 16+
4. pnpm 版本 6.x

# 克隆项目
git clone https://github.com/un-pany/v3-admin-vite.git

# 进入项目目录
cd v3-admin-vite

# 安装依赖
pnpm i

# 启动服务
pnpm dev
```

## ✔️ 预览

```bash
# 预览预发布环境
pnpm preview:stage

# 预览正式环境
pnpm preview:prod
```

## 📦️ 多环境打包

```bash
# 构建预发布环境
pnpm build:stage

# 构建正式环境
pnpm build:prod
```

## 🔧 代码格式检查

```bash
pnpm lint
```

## Git 提交规范

- `feat` 增加新功能
- `fix` 修复问题/BUG
- `style` 代码风格相关无影响运行结果的
- `perf` 优化/性能提升
- `refactor` 重构
- `revert` 撤销修改
- `test` 测试相关
- `docs` 文档/注释
- `chore` 依赖更新/脚手架配置修改等
- `workflow` 工作流改进
- `ci` 持续集成
- `types` 类型定义文件更改
- `wip` 开发中
- `mod` 不确定分类的修改

## 可有可无的群

QQ群：1014374415（左）&& 加我微信，拉你进微信群（右）

![qq.png](https://github.com/un-pany/v3-admin-vite/blob/main/src/assets/docs/qq.png)
![wechat.png](https://github.com/un-pany/v3-admin-vite/blob/main/src/assets/docs/wechat.png)

## 📄 License

[MIT](https://github.com/un-pany/v3-admin-vite/blob/main/LICENSE)

Copyright (c) 2022 pany
