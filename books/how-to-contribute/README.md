# 简介
`最后更新：2016 年 4 月 24 日`

本书将介绍如何参与到 HeckPsi Education 计划中。每个参与新建、修改、更新公开课程的社区参与者都是极度欢迎的。
目前 HeckPsi Education 仍然处于测试阶段，目前所有制订的规则，最终都可能发生改变。

## 基本概念
HeckPsi Education 的基本构成是「书」，每本书都是一个独立的项目，被独立维护和讨论。
但是由于我们使用 Git 作为版本管理工具，无法将每本书作为文件夹单独管理。
这使得，如果你需要参与这项工作你需要下载整个 HeckPsi Education 项目下的全部书。
但是，请放心，由于这些数据是纯文字，下载整个项目也不会占用太大的容量，每次提交也会是增量的所以也不会有很大的流量开销。
在未来，我们会引入在线编辑器，以避免下载全部项目。

HeckPsi Education 中的每一本书其本质是一个 GitBook 项目，你需要了解一些基本的 GitBook 和 Markdown 的相关知识，
以是你能正常参与编辑这个项目中。

## 协议
所有提交于 HeckPsi Education 的书，都遵守 [CC BY-NC-SA 3.0](https://creativecommons.org/licenses/by-nc-sa/3.0/) 协议。
任何人在非商业使用、署名和相同方式分享的前提下被允许分享和演绎。

## 工作流
HeckPsi Education 项目在 Github 上维护，其具体工作流程基于简单的 Fork -> Pull Request 的模式。

```
+---------+
| Project |  a ----> b ----> c ----> e ----> g
+---------+          |               |       ^
                     | Fork          | Merge | Pull Request
+---------+          v               v       |
|  Local  |          b ----> d ----+ f ------+
+---------+            Edit
```
