# 🥞 Coinhunters UIkit

[![Version](https://img.shields.io/npm/v/@coinhunters/uikit)](https://www.npmjs.com/package/@coinhunters/uikit) [![Size](https://img.shields.io/bundlephobia/min/@coinhunters/uikit)](https://www.npmjs.com/package/@coinhunters/uikit)

Coinhunters UIkit is a set of React components and hooks used to build pages on Coinhunters's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @coinhunters/uikit`

## Setup

### Theme

Before using Coinhunters UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@coinhunters/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@coinhunters/uikit'
...
<ResetCSS />
```
