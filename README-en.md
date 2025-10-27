# Vue3 Snippets

🔥 This snippets only support vue3 + pinia + router + ts/js.

❄️ This extension is still under development, you can see the progress in the todo table

## Features

Make the syntax closer to Vue3, the whole will be biased towards combination, and the selection needs to be suffixed with `-opt`

- init vue file start with `vbase`
- use option with `-opt` below prefix. such as `vbase-opt`
- pinia support start with `pinia`
- router support start with `router`
- vite support start with `vite`

### Vue 3.5+ New Features Support

This extension now supports the latest features of Vue 3.5, including:

#### Reactive Syntax Sugar
- `$ref`, `$computed`, `$shallowRef`, `$customRef`, `$toRef` and other reactive transformation syntax

#### SSR Enhancements
- `useId` API for server-side rendering
- Lazy Hydration for performance
- Enhanced defineCustomElement API

#### Reactive and Custom Elements Enhancements
- Reactive Props destructuring (destructured props maintain reactivity)
- useHost API for Custom Elements
- useShadowRoot API for Custom Elements

#### Performance Optimizations
- Static hoisting optimization
- Patch Flags render optimization
- Shallow Ref performance optimization
- Object.freeze performance optimization
- Async component performance optimization
- Lazy Hydration configuration
- Proxy-based reactive system optimization
- Computed property caching optimization

#### useTemplateRef
- useTemplateRef quick declaration
- Template reference template

### Router Features

Router-related snippets all start with `router` prefix:

- `router-route` - Create route configuration item
- `router-component` - Create route component import statement
- `vscrollbehavior` - Router scroll behavior configuration
- `vbeforeeach` - Global前置 guard
- `vbeforeresolve` - Global resolve guard
- `vaftereach` - Global后置 guard
- `vbeforeenter` - Route exclusive guard
- `vbeforerouteenter` - Component guard - before enter
- `vbeforerouteupdate` - Component guard - when update
- `vbeforerouteleave` - Component guard - before leave

### Vue Template Features

Vue template-related snippets include:

- `vfor` - v-for loop statement
- `vmodel` - v-model two-way binding
- `vmodel-num` - Number input v-model binding
- `von` - v-on event binding shorthand
- `vel-props` - Component element with props
- `vslot-named` - Named slot
- `vsrc` - Image resource binding
- `vstyle` - Inline style binding
- `vclass` - Class name binding
- `vanim` - Transition animation component
- `vnuxtl` - Nuxt routing link
- `vroutename` - Named routing link
- `vroutepath` - Path routing link

### TODO

- [x]  vue初始化代码片段
- [x]  vue模板
- [x]  pinia
- [x]  router
- [x]  vite

## Reference

- [Vue VSCode Snippets](https://marketplace.visualstudio.com/items?itemName=sdras.vue-vscode-snippets)
