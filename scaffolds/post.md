---
title: {{ title }}
date: {{ date }}
tags: 
author: gongfpp https://github.com/gongfpp
---




# MARKDOWN 常用语法 + HTML扩展语法
两个空格后回车，  
则换行

> 我是引用

`printf("我是代码");`

```java
public static void main(String[] args) {
     System.out.println("我是java");
}
```

```python
print("我是python")
```

[点击跳转至百度](http://www.baidu.com)

![图片](https://img-blog.csdnimg.cn/8b5321892a51473eaf2e2f6ef4273660.png)  
注： 引用图片和链接的唯一区别就是在最前方添加一个感叹号。


- 黄瓜
- 玉米
- 茄子

1. 黄瓜
2. 玉米
3. 茄子

*    段落一 空四个空格  
阿斯蒂芬阿斯蒂芬
     小段一
*    段落二

     小段二
     
***
这俩都是分隔符  

---

| 表头  | 条目一 |  条目二  |
| :---: | :-: | :------------------------------------: |
| 项目  | 项目一 |  项目二  |
| 啊 啊 |   啊   | 爱的色放 |

我们可以设置表格的对齐方式：
-: 设置内容和标题栏居右对齐。
:- 设置内容和标题栏居左对齐。
:-: 设置内容和标题栏居中对齐。

> 注：三个短斜杠左右的冒号用于控制对齐方式，只放置左边冒号表示文字居左，只放置右边冒号表示文字居右，如果两边都放置冒号表示文字居中。 ```-```符号数量不影响


<font size="4" color="red">字体</font>  
<font size="4" color="#1ffac"><u>下划线</u>字体</font>

[放一个选色网站 十六进制 RGBA](http://tools.rockhwhuang.com/)

<font face="黑体">实现字体为黑体</font>  
<small>比默认字体小一号</small>  
这里显示的是浏览器默认字体大小  
<font size=1>实现字体大小改变</font>  
<big>比默认字体大一号</big>  
<font color=red>实现字体颜色为红色</font>  
<span style="background-color: orange">实现背景填充为橙色</span>  
<font color=#FF69B4>颜色值用十六进制表示，实现字体颜色为“热情的粉红”</font>  
<span style="background-color: #D3D3D3">颜色值用十六进制表示，实现背景填充为“浅灰色”</span>  
<font face="黑体" size=4 color=red >实现字体效果：黑体、4号、红色</font>  
<span style="background-color: #D3D3D3"><font size=4 color=#DC143C>默认字体，猩红色，4号，浅灰色填充</font></span>

H<sub>2</sub>O  
注册商标<sup>&reg;</sup>  
(x<sub>1</sub>+x<sub>2</sub>)<sup>2</sup> = x<sub>1</sub><sup>2</sup>+x<sub>2</sub><sup>2</sup>+2x<sub>1</sub>x<sub>2</sub>

如果文本不是超链接，就不要<u>对其使用下划线</u>。

&ensp;缩进&emsp;缩进 

<span style="text-decoration: overline;">RESET</span>是复位信号，输入低电平有效。

可以用```<div>```结合```align```控制图片居中对齐
<div align="center"><img src="https://img-blog.csdnimg.cn/8b5321892a51473eaf2e2f6ef4273660.png" />图注1 图文无关</div>  

## 符号
| 字符  | 实体编号 | 实体名称 |  描述   |
| :---: | :------: | :------: | :-----: |
|   ∀   |` &#8704; ` | `&forall;` | for all |
|   ∂   |` &#8706; ` | ` &part; ` |  part   |
|   ∃   |` &#8707; ` | `&exist; ` | exists  |
|   ∅   |` &#8709; ` | `&empty; ` |  empty  |
|   ∇   |` &#8711; ` | `&nabla; ` |  nabla  |
|   ∈   |` &#8712; ` | ` &isin; ` |  isin   |
|   ∉   |` &#8713; ` | `&notin; ` |  notin  |
|   ∋   |` &#8715; ` | `  &ni;  ` |   ni    |
|   ∏   |` &#8719; ` | ` &prod; ` |  prod   |
|   ∑   |` &#8721; ` | ` &sum;  ` |   sum   |

编号+ `&#   ;` 如 ```&#9812;``` :&#9812;  或 `&名字;` 如 `&exist;`:&exist;

[所有的杂项符号参考](https://www.w3school.com.cn/charsets/ref_utf_symbols.asp)  
[所有的箭头符号参考](https://www.w3school.com.cn/charsets/ref_utf_arrows.asp)

