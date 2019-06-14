---
layout: post
title: '[CSS]01. CheatSheet'
author: emily.choi
date: 2019-05-09 09:00
tags: [css]
image: /files/covers/css.png
---
# css

## Lesson 1: Cheat Sheet

### **CSS** 
- CSS: Cascading Style Sheets

#### 1. Structures

```html
<style>
selector{
  property: value;
  property2: value2;
}
</style>

<html>
  <body>
    <selector>
    </selector>
    </body>
  </html>
```

#### 2. Style

![IMAGE](/files/box.png)
<!-- .element height="50%" width="50%" -->
<img src="/files/box.png" height="200">



```html
<style>
content{
  padding: 1px auto 1px auto;
  border-width: 1px;
  border-sytle: solid/double/none; 
  border-color: red;
  border: 1px solid red;
  margin: 2px auto 2px auto;
}
</style>

<html>
  <body>
    <content>
    </content>
    </body>
  </html>
```

- align

```html
<style>
  /* center align */
selector{
  text-align: center/left/right/justify; 
  /* or */
  margin: auto;
  width: 100px;
}
</style>

<html>
  <body>
    <selector>
    </selector>
    </body>
  </html>
```

- link style

```html
<style>
a:link{
  /* default status */
  color: value;
  text-decoration: value2;
}
a:visited{
/* after visited */
}
a:hover{
/* mouse over */
}
a:active{
/* clicking status */
}
a:focus{
/* cliked status */
}
</style>

<html>
  <body>
    <a href="www.example.com">website_link</a> 
    </body>
  </html>
```

- font

```html
<style>
selector{
  font-family: Arial, Verdana;
  color : yellow;
  font-size: 16px; /* default value */
  font-weight: bold;
}
</style>

<html>
  <body>
    <selector>
    </selector>
  </body>
</html>
```

- text

```html
<style>
selector{
  text-decoration: none/underline/overline/line-through;

  text-transform: uppercase/lowercase/capitalize;

  letter-spacing: 0.2em;
  word-spacing: 1em;
}
</style>

<html>
  <body>
    <selector>
    </selector>
  </body>
</html>
```


> refer to this website [CSS CheatSheet](https://html-css-js.com/css/).

