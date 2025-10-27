# Vue3 Snippets

🔥 这个snippets只支持vue3 + pinia + router + vite + ts/js。

❄️这个扩展还在开发中，你可以在 todo 表中看到进度

## 特性

本插件让语法更接近Vue3，整体会偏向 Composition API，Options-based API需要后缀 `-opt`

- 初始化vue文件前缀为 `vbase`
- 对pinia支持前缀为 `pinia`
- 对router支持前缀为 `router`
- 对vite支持前缀为 `vite`
- 使用选项式要在前缀后面添加 `-opt`。例如 `vbase-opt`

### 路由(router)功能

路由相关的代码片段前缀都以 `router` 开头：

- `router-route` - 创建路由配置项
- `router-component` - 创建路由组件导入语句
- `vscrollbehavior` - 路由滚动行为配置
- `vbeforeeach` - 全局前置守卫
- `vbeforeresolve` - 全局解析守卫
- `vaftereach` - 全局后置守卫
- `vbeforeenter` - 路由独享守卫
- `vbeforerouteenter` - 组件内守卫 - 进入前
- `vbeforerouteupdate` - 组件内守卫 - 更新时
- `vbeforerouteleave` - 组件内守卫 - 离开前

### Vue模板(vue-template)功能

Vue模板相关的代码片段前缀包括：

- `vfor` - v-for循环语句
- `vmodel` - v-model双向绑定
- `vmodel-num` - 数字输入框的v-model绑定
- `von` - v-on事件绑定简写
- `vel-props` - 带有props的组件元素
- `vslot-named` - 具名插槽
- `vsrc` - 图片资源绑定
- `vstyle` - 内联样式绑定
- `vclass` - 类名绑定
- `vanim` - 过渡动画组件
- `vnuxtl` - Nuxt路由链接
- `vroutename` - 命名路由链接
- `vroutepath` - 路径路由链接

### TODO

- [x]  vue初始化代码片段
- [ ]  vue模板
- [x]  pinia
- [x]  router
- [x]  vite

## 参考

- [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)
