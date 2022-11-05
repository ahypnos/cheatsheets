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

Basic
---------------
{: .-three-column}

### Project

| Code          | Description                    |
| ------------- | ------------------------------ |
| `<SPC> p p`   | switch project                 |
| `<SPC> p a`   | add project                    |
| ---           | ---                            |
| `<SPC> <SPC>` | find file in project           |
| `<SPC> /`     | text search keyword in project |
| ---           | ---                            |

### Go Mode


| Code  | Description      |
| ----- | ---------------- |
| `g d` | go to definition |
| `g D` | go to reference  |
| ----- | ---------------  |

### Move

| Code      | Description                                   |
| --------- | --------------------------------------------- |
| `*`       | search current word                           |
| `#`       | search current word                           |
| `C-o`     | jump back                                     |
| `C-i`     | jump forward                                  |
| `f{char}` | forward to the next occurrence of {char}      |
| `F{char}` | backward to the previous occurrence of {char} |
| `w`       | forward to start of next word                 |
| `b`       | backward to previous ‘start of word’          |
| `e`       | forward to next ‘end of word’                 |
| `ge`      | backward to end of previous word              |
| -----     | ---------------                               |