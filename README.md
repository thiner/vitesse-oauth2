<p align='center'>
  <img src='https://user-images.githubusercontent.com/11247099/111864893-a457fd00-899e-11eb-9f05-f4b88987541d.png' alt='Vitesse - Opinionated Vite Starter Template' width='600'/>
</p>

# Vitesse OAuth2

<h6 align='center'>
<a href="https://vitesse-lite.netlify.app/">Live Demo</a>
</h6>

<h5 align='center'>
<b>Lightweight version of <a href="https://github.com/antfu/vitesse">Vitesse</a> with OAuth2 support</b>
</h5>

<br>

<p align='center'>
<b>English</b> | <a href="https://github.com/thiner/vitesse-oauth2/blob/main/README.zh-CN.md">简体中文</a>
<!-- Contributors: Thanks for getting interested, however we DON'T accept new translations to the README, thanks. -->
</p>

## Features

- ⚡️ [Vue 3](https://github.com/vuejs/core), [Vite 3](https://github.com/vitejs/vite), [pnpm](https://pnpm.io/), [ESBuild](https://github.com/evanw/esbuild) - born with fastness

- 🗂 [File based routing](https://github.com/thiner/vitesse-oauth2/tree/main/src/pages)

- 📦 [Components auto importing](https://github.com/thiner/vitesse-oauth2/tree/main/src/components)

- 🎨 [UnoCSS](https://github.com/antfu/unocss) - The instant on-demand atomic CSS engine.

- 😃 Use icons from any icon sets in [Pure CSS](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

- 🔥 Use the [new `<script setup>` style](https://github.com/vuejs/rfcs/pull/227)

- ✅ Use [Vitest](http://vitest.dev/) for unit and components testing

- 🦾 TypeScript, of course

- ☁️ Deploy on Netlify, zero-config

- 🔐 OAuth2 authentication support


<br>

See [Vitesse](https://github.com/antfu/vitesse) for full featureset.

## Dropped Features

The following features from [Vitesse](https://github.com/antfu/vitesse) have been removed:

- ~~i18n~~
- ~~Layouts~~
- ~~SSG~~
- ~~PWA~~
- ~~Markdown~~

## Pre-packed

### UI Frameworks

- [UnoCSS](https://github.com/antfu/unocss) - The instant on-demand atomic CSS engine.

### Icons

- [Iconify](https://iconify.design) - use icons from any icon sets [🔍Icônes](https://icones.netlify.app/)
- [Pure CSS Icons via UnoCSS](https://github.com/antfu/unocss/tree/main/packages/preset-icons)

### Plugins

- [Vue Router](https://github.com/vuejs/vue-router)
  - [`vite-plugin-pages`](https://github.com/hannoeru/vite-plugin-pages) - file system based routing
- [`unplugin-auto-import`](https://github.com/antfu/unplugin-auto-import) - Directly use Vue Composition API and others without importing
- [`unplugin-vue-components`](https://github.com/antfu/unplugin-vue-components) - components auto import
- [`unplugin-vue-macros`](https://github.com/sxzz/unplugin-vue-macros) - Explore and extend more macros and syntax sugar to Vue.
- [VueUse](https://github.com/antfu/vueuse) - collection of useful composition APIs

## OAuth2 Integration

This template extends Vitesse Lite with OAuth2 authentication capabilities, allowing you to:

- Easily integrate with OAuth2 providers (Google, GitHub, etc.)
- Manage authentication state with Vue
- Protect routes that require authentication
- Handle token refresh and session management

## Try it now!

### GitHub Template

[Create a repo from this template on GitHub](https://github.com/thiner/vitesse-oauth2/generate).

### Clone to local

If you prefer to do it manually with the cleaner git history

```bash
npx degit thiner/vitesse-oauth2 my-vitesse-oauth2-app
cd my-vitesse-oauth2-app
pnpm i # If you don't have pnpm installed, run: npm install -g pnpm
```
