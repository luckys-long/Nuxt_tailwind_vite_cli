# Nuxt 3 Starter Kit

技术栈 Vite, Vue 3, TypeScript, PostCSS, and TailwindCSS.

## Features

This starter kit includes the following technologies:

- **Nuxt 3**: A Vue 3 framework for modern web applications.
- **Vite**: A fast and lightweight bundler for quick development.
- **TypeScript**: A typed superset of JavaScript for improved developer experience and reduced bugs.
- **TailwindCSS**: A utility-first CSS framework for rapid UI development.



```vue
<template>
  <span class="text-red-500">This is red</span>
</template>
```

Example 2 (using a 'semantic' class name):

```vue
<template>
  <span class="some-red-span">This is red</span>
</template>

<style lang="postcss">
.some-red-span {
  @apply text-red-500;
}
</style>
```


