# Vue 3 + Vite

This template should help get you started developing with Vue 3 in Vite. The template uses Vue 3 `<script setup>` SFCs, check out the [script setup docs](https://v3.vuejs.org/api/sfc-script-setup.html#sfc-script-setup) to learn more.

## Recommended IDE Setup

- [VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=johnsoncodehk.volar)

## 一、创建Vue3.0 工程

> ### 1. 使用 vue-cli 创建

[官方文档](https://v3.cn.vuejs.org/guide/installation.html#%E5%91%BD%E4%BB%A4%E8%A1%8C%E5%B7%A5%E5%85%B7-cli) 

```bash
## 查看@vue/cli版本，确保@vue/cli版本在4.5.0以上
vue --version

## 安装或者升级你的@vue/cli
npm install -g @vue/cli

## 创建
vue create <project-name>

## 启动
cd <project-name>
npm run serve
```

>### 2. 使用 Vite 创建

[官方文档](https://v3.cn.vuejs.org/guide/installation.html#vite)

```sh
## 查看npm 版本
npm -v
## npm 6.x
$ npm init vite@latest <project-name> --template vue

## npm 7+，需要加上额外的双短横线
$ npm init vite@latest <project-name> -- --template vue

## 启动
$ cd <project-name>
$ npm install
$ npm run dev
```

## 二、使用 Naive UI

[官方文档](https://www.naiveui.com/zh-CN/os-theme)

