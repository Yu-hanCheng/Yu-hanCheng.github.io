---
title: WTForm render
date: 2019-01-03 21:32:29
tags: ['python','WTForm']
categories: 'python'
---
在html中
```
<link rel="stylesheet" href="/static/basic.css" />
{{ wtf.quick_form(form,button_map={'submit': 'success'},extra_classes="label") }}
```
在 css中
```
.label_loginform {
    color: white;
    text-align: left;
    font-size: medium;

}
```