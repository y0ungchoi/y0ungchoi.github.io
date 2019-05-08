---
layout: post
title: '[HTML]01. CheatSheet'
author: emily.choi
date: 2019-04-29 13:00
tags: [html]
image: /files/covers/html.png
---
# HTML

## Lesson 1: HTML CheatSheet

### **HTML**
- HTML: HyperText Markup Language

### **CheatSheet**

#### 1. Tags
 - headings
 
```html
<h1>Page title</h1>
<h2>Subheading</h2>
<h3>Tertiary heading</h3>
<h4>Quaternary heading</h4>
```

 - paragraph
 
```html
<p style="text-align: center;">text</p>
```

 - fonts
 
 ```html
 <strong>Bold text</strong>
 <em>Italic text</em>
 <span style="text-decoration: underline;">Underlined text</span>
```
 - comment
 
 ```html
 <!-- HTML Comment -->
```

 - quotation

```html
<q>Success is a journey not a destination.</q>
<blockquote cite="https://ruwix.com/">
The Rubik's Cube is the World’s best selling puzzle toy.
</blockquote> 
```

 - line

```html
horizontal line
<hr />

line break
<br>
```

#### 2. Structures

 - list

```html
ordered lost
<ol>
  <li>First</li>
  <li>Second</li>
  <li>Third</li>
</ol>

unordered list
<ul>
  <li>First</li>
  <li>Second</li>
  <li>Third</li>
</ul>
```

#### 3. Attributes
 - link

```html
<a href= "https://htmlcheatsheet.com/" target="_blank"> html cheatsheet</a> 


<a href= "../index.html"> top</a>
```

 - image
	- format: jpg, gif, png
	
```html
<img src="/demo.jpg" alt="description" height="48" width="100" align="top/middle/bottom/left/right/" />

caption
<figure>
<img src="../images/otters.jpg" />
<figcaption> 바다 수달이 손을 잡고 자고 있어요</figcaption> 
</figure>
```

#### 4. Table

```html
<table border="1" bgcolor="pink"
	<tr> -->행
		<th></th>
		<th scope="col"> 행1</th>
		<th scope="col"> 행2</th>
	</tr>
	<tr>
		<th></th>
		<th scope="row"> 열1</th>
		<td>1,1</td>
		<td>1,2</td>
	</tr>
	<tr>
		<th></th>
		<th scope="row"> 열2</th>
		<td>2,1</td>
		<td>2,2</td>
	</tr>
</table>
```


> refer to this website [HTML CheatSheet](https://htmlcheatsheet.com/).

