---
title: "Vim" # Title of the blog post.
date: 2021-01-19T10:43:58+08:00 # Date of post creation.
toc: true # Controls if a table of contents should be generated for first-level links automatically.
categories:
  - note
tags:
---

**Insert Lead paragraph here.**

## 移动

### 定位
| 动作 | 普通模式 |
| - | - |
| [num:1]h | 左移[num:1]字符 |
| [num:1]j | 下移[num:1]字符 |
| [num:1]k | 上移[num:1]字符 |
| [num:1]l | 右移[num:1]字符 |
| 0 | 本行行首 |
| ^ | 本行行第一个非空字符 |
| $ | 本行行尾 |
| w | 本行下一个词首 |
| b | 本行上一个词首 |
| e | 本行下一个词首 |
| G | 本文件结尾 |
| gg | 文件起始 |
| * | 文件下一个光标所在单词处 |
| # | 文件上一个光标所在单词处 |
| /{string} | 文件搜索下一个{string}处 |
| ?{string} | 文件搜索上一个{string}处 |
| n | 继续/{string}或?{string}文件搜索下一个{string}处 |
| N | 继续/{string}或?{string}文件搜索上一个{string}处 |
| :{rownum} | 跳转到{rownum}行 |
| f{char} | 跳转到本行下一个{char}处 |
| [f{char}]; | 继续f{char}跳转到下一个{char}处 |
| [f{char}], | 继续f{char}跳转到上一个{char}处 |
| C-b | 上一屏 |
| C-f | 下一屏 |
| C-u | 上半屏 |
| C-d | 下半屏 |
## 折叠
| 动作 | 普通模式 |
| - | - |
| zm |  |
| zM |  |
| zo |  |
| zO |  |
| zc |  |
| zC |  |
| zr |  |
| zR |  |

