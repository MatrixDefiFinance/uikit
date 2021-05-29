# 🥞 MatrixDefi UIkit

[![Version](https://img.shields.io/npm/v/@matrixpilldefi/uikit)](https://www.npmjs.com/package/@matrixpilldefi/uikit) [![Size](https://img.shields.io/bundlephobia/min/@matrixpilldefi/uikit)](https://www.npmjs.com/package/@matrixpilldefi/uikit)

MatrixDefi UIkit is a set of React components and hooks used to build pages on MatrixDefi's apps. It also contains a theme file for dark and light mode.

## Install

`yarn add @matrixpilldefi/uikit`

## Setup

### Theme

Before using MatrixDefi UIkit, you need to provide the theme file to styled-component.

```
import { ThemeProvider } from 'styled-components'
import { light, dark } from '@matrixpilldefi/uikit'
...
<ThemeProvider theme={isDark}>...</ThemeProvider>
```

### Reset

A reset CSS is available as a global styled component.

```
import { ResetCSS } from '@matrixpilldefi/uikit'
...
<ResetCSS />
```
