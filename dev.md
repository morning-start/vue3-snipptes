# Vue3 Snippets 开发者文档

本文档旨在为开发者提供关于如何使用和扩展 Vue3 Snippets 的详细指南。

## 目录结构

```
snippets/
├── ignore.code-snippets
├── pinia.code-snippets
├── router.code-snippets
├── vite.code-snippets
├── vue-init.code-snippets
├── vue-script.code-snippets
└── vue-template.code-snippets
```

## 代码片段分类

### 1. Vue 初始化代码片段 (`vue-init.code-snippets`)

提供多种 Vue 单文件组件的初始化模板：

- `vbase` - 基础的 Vue 组合式 API 模板 (JavaScript)
- `vbase-scss` - 使用 SCSS 样式的 Vue 模板
- `vbase-less` - 使用 Less 样式的 Vue 模板
- `vbase-stylus` - 使用 Stylus 样式的 Vue 模板
- `vbase-postcss` - 使用 PostCSS 样式的 Vue 模板
- `vbase-ts` - 基础的 Vue 组合式 API 模板 (TypeScript)
- `vbase-ts-scss` - 使用 SCSS 样式的 Vue 模板 (TypeScript)
- `vbase-ts-less` - 使用 Less 样式的 Vue 模板 (TypeScript)
- `vbase-ts-stylus` - 使用 Stylus 样式的 Vue 模板 (TypeScript)
- `vbase-ts-postcss` - 使用 PostCSS 样式的 Vue 模板 (TypeScript)

选项式 API 模板（添加 `-opt` 后缀）：
- `vbase-opt` - 基础的 Vue 选项式 API 模板 (JavaScript)
- `vbase-opt-scss` - 使用 SCSS 样式的 Vue 模板 (选项式)
- `vbase-opt-ts` - 基础的 Vue 选项式 API 模板 (TypeScript)
- 等等...

### 2. Pinia 代码片段 (`pinia.code-snippets`)

用于 Pinia 状态管理的代码片段：

- `pinia-store-init` - 初始化 Pinia store (组合式)
- `pinia-store-use` - 使用 Pinia store
- `pinia-state-dest` - 解构 Pinia 状态
- `pinia-action-dest` - 解构 Pinia 动作
- `pinia-state-reset` - Pinia 状态重置函数
- `pinia-opt-store-init` - 初始化 Pinia store (选项式)
- `pinia-opt-getter` - Pinia getter (选项式)
- `pinia-opt-getter-arrow` - Pinia getter 箭头函数 (选项式)
- `pinia-opt-action` - Pinia action (选项式)

### 3. Vue Router 代码片段 (`router.code-snippets`)

用于 Vue Router 的代码片段：

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

### 4. Vite 代码片段 (`vite.code-snippets`)

用于 Vite 配置的代码片段：

- `vite-src` - Vite 配置添加 @ 别名

### 5. Vue 模板代码片段 (`vue-template.code-snippets`)

用于 Vue 模板的代码片段：

- `vfor` - v-for 循环语句
- `vmodel` - v-model 双向绑定
- `vmodel-num` - 数字输入框的 v-model 绑定
- `von` - v-on 事件绑定简写
- `vel-props` - 带有 props 的组件元素
- `vslot-named` - 具名插槽
- `vsrc` - 图片资源绑定
- `vstyle` - 内联样式绑定
- `vstyle-obj` - 对象形式的内联样式绑定
- `vclass` - 类名绑定
- `vclass-obj` - 对象形式的类名绑定
- `vclass-obj-mult` - 多条件类名绑定
- `vanim` - 过渡动画组件
- `vnuxtl` - Nuxt 路由链接
- `vroutename` - 命名路由链接
- `vroutenameparam` - 带参数的命名路由链接
- `vroutepath` - 路径路由链接
- `vemit-child` - 子组件触发事件
- `vemit-parent` - 父组件监听事件

### 6. Vue 脚本代码片段 (`vue-script.code-snippets`)

用于 Vue 脚本部分的代码片段：

- `vdata` - Vue 组件数据
- `vmethod` - Vue 方法
- `vcomputed` - 计算属性
- `vbeforecreate` - beforeCreate 生命周期钩子
- `vcreated` - created 生命周期钩子
- `vbeforemount` - beforeMount 生命周期钩子
- `vmounted` - mounted 生命周期钩子
- `vbeforeupdate` - beforeUpdate 生命周期钩子
- `vupdated` - updated 生命周期钩子
- `vbeforedestroy` - beforeDestroy 生命周期钩子 (Vue 2 钩子已废弃，请使用 v3onbeforeunmount)
- `vdestroyed` - destroyed 生命周期钩子 (Vue 2 钩子已废弃，请使用 v3onunmounted)
- `vwatcher` - Vue 监听器
- `vwatcher-options` - 带选项的 Vue 监听器
- `vprops` - Vue Props 定义
- `vimport` - 导入组件
- `vcomponents` - 注册组件
- `vimport-export` - 导入并注册组件
- `vimport-dynamic` - 动态导入组件
- `vmapstate` - 映射状态
- `vmapgetters` - 映射 getters
- `vmapmutations` - 映射 mutations
- `vmapactions` - 映射 actions
- `vfilter` - Vue 过滤器
- `vmixin` - Vue mixin 定义
- `vmixin-use` - 使用 Vue mixin
- `vc-direct` - 自定义指令
- `vimport-lib` - 导入库
- `vimport-gsap` - 导入 GSAP 动画库
- `vanimhook-js` - JavaScript 动画钩子
- `vcommit` - Vuex commit
- `vdispatch` - Vuex dispatch
- `vtest` - 测试代码模板
- `vconfig` - 配置对象
- `v3reactive` - Vue 3 reactive API
- `v3computed` - Vue 3 computed API
- `v3watch` - Vue 3 watch API
- `v3watch-array` - Vue 3 监听数组
- `v3watcheffect` - Vue 3 watchEffect API
- `v3ref` - Vue 3 ref API
- `v3onmounted` - Vue 3 onMounted 生命周期钩子
- `v3onbeforemount` - Vue 3 onBeforeMount 生命周期钩子
- `v3onbeforeupdate` - Vue 3 onBeforeUpdate 生命周期钩子
- `v3onupdated` - Vue 3 onUpdated 生命周期钩子
- `v3onerrorcaptured` - Vue 3 onErrorCaptured 生命周期钩子
- `v3onunmounted` - Vue 3 onUnmounted 生命周期钩子
- `v3onbeforeunmount` - Vue 3 onBeforeUnmount 生命周期钩子
- `vplugin` - 插件定义
- `v3reactive-setup` - 在 setup 中使用 reactive
- `v3useinoptions` - 在选项式 API 中使用组合式 API
- `vdefineprops` - Vue 3 defineProps API (带类型推导)
- `vdefineemits` - Vue 3 defineEmits API
- `vdefineexpose` - Vue 3 defineExpose API
- `vdefinemodel` - Vue 3 defineModel API (用于 v-model 的新语法糖，Vue 3.4+)
- `vuseref` - Vue 3 ref 快速声明
- `vusecomputed` - Vue 3 computed 快速声明
- `vusewatch` - Vue 3 watch 快速声明
- `vuseonmounted` - Vue 3 onMounted 快速声明

### 7. 忽略文件代码片段 (`ignore.code-snippets`)

- `gitignore` - 生成 .gitignore 文件内容

## 开发指南

### 添加新的代码片段

1. 选择合适的代码片段文件，或者创建一个新的 `.code-snippets` 文件
2. 遵循以下格式添加代码片段：

```json
{
  "Snippet Name": {
    "prefix": "snippet-prefix",
    "body": [
      "代码行1",
      "代码行2",
      "${1:占位符1}",
      "${2:占位符2}"
    ],
    "description": "代码片段描述"
  }
}
```

### 占位符语法

- `${1:placeholder}` - 第一个可编辑位置，默认值为 "placeholder"
- `$1` - 不带默认值的第一个可编辑位置
- `${2:another}` - 第二个可编辑位置
- `$0` - 最终光标位置

### 注册代码片段

在 `package.json` 的 `contributes.snippets` 部分添加新代码片段文件的引用：

```json
{
  "language": "目标语言",
  "path": "./snippets/文件名.code-snippets"
}
```

### Vue 3.4+ 组合式 API 代码片段

新增的 `vdefineprops`、`vdefineemits`、`vdefineexpose` 和 `vdefinemodel` 代码片段是 Vue 3.4+ 中推荐使用的组合式 API 模式。这些代码片段提供了更简洁的语法来定义组件的 props、emits、暴露的属性以及 v-model 的实现。

新增的 `vuseref`、`vusecomputed`、`vusewatch` 和 `vuseonmounted` 代码片段是常用的组合式 API 的快速声明方式，可以帮助开发者更快地编写 Vue 3 代码。

## 发布流程

1. 更新 `package.json` 中的版本号
2. 更新 `CHANGELOG.md` 文件记录变更
3. 提交更改到 GitHub
4. 发布到 Visual Studio Code Marketplace