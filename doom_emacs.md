---
title: Doom Emacs
category: CLI
layout: 2017/sheet
tags: [Featured]
updated: 2020-07-05
keywords:
  - Project
  - Functions
  - Interpolation
  - Brace expansions
  - Loops
  - Conditional execution
  - Command substitution
---

Project
---------------


| Code              | Description         |
| ----------------- | ------------------- |
| `${FOO%suffix}`   | Remove suffix       |
| `${FOO#prefix}`   | Remove prefix       |
| ---               | ---                 |
| `${FOO%%suffix}`  | Remove long suffix  |
| `${FOO##prefix}`  | Remove long prefix  |
| ---               | ---                 |
| `${FOO/from/to}`  | Replace first match |
| `${FOO//from/to}` | Replace all         |
| ---               | ---                 |
| `${FOO/%from/to}` | Replace suffix      |
| `${FOO/#from/to}` | Replace prefix      |