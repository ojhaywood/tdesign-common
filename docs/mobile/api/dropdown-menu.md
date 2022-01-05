---
title: DropdownMenu 下拉菜单
description: 菜单呈现数个并列的选项类目，用于整个页面的内容筛选，由菜单面板和菜单选项组成。
spline: base
isComponent: true
toc: false
---

### 单选下拉菜单

用于选择项需要单选的场景

{{ single-choice }}

### 多选下拉菜单

用于选择项可以进行多选的场景
选择后标签不改变名称，标题最多展示 4 个字符超出“…”处理
多选下拉菜单根据选择项内容的差异，可以有以下不同的样式

{{ options-layout }}

### 树形下拉菜单

用于选择项需要多级选择的场景 例如地区、区域、食物的选择

{{ tree-menu }}

### 禁用菜单/选项

{{ disabled }}

### 自定义选单

{{ customized-menu }}

**注意：同时指定了 `options` 属性和内部自定义内容时，将优先展示自定义内容。**