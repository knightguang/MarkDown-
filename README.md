# MarkDown-

1. 一开始，先记住 `# 这是标题`、`## 这是二级标题`、`### 这是三级标题`
这时候你写一般小文章会开始感觉 MD 不错。

2. 然后，你发现标题不适合做列表，记住了用`1. 第一点`、`- 这一点`来列表超级方便。

3. 好吧，写知乎答案总要有些重点吧，`**加粗**`、`*斜体*`、`~~删除线~~`开始派上用场了。
这时你基本不会打开 Word 那样的笨重软件了。
>**这个我见过，是黑体**
<br />*听说这样是斜体哦*
<br />~~删除线？什么鬼哦~~

4. 如果你不幸是码农： 
`\`这是单行代码\``
<br />'单行Demo嘛'

//这是代码段，四个空格或一个制表符缩进
int i;

> 这是引用

5. 你越来越喜欢，自然会去查查维基（Markdown）还有什么语法，加上多用，很快就基本掌握了。
MD 还有表格、锚、注脚、贴图等。强烈推荐 Mou，按 ⌘＋R 可以快速查看语法。

6. 慢慢，你会发现，总有小「bugs」，如列表内无法内嵌代码段。上网查查，你开始理解 MD 的缩进内嵌机制等高级隐形内容，这样你就 Master 了！

---
# on my time
- - -
> yes 缩进4个空格

    this is normal paragraph
    this is a preformatted
       code block
---

>now 缩进一个制表符

	this is a preformatted
		code block
		 	yes is right
---

***

***

---
[听说这样是链接][http://www.jianshu.com/notebooks/4128032/latest]
<br />[什么鬼哦，这才是链接好么](www.jianshu.com)
<br />[楼上不科学，链接是要加HTTP的~](http://www.jianshu.com/notebooks/4128032/latest)
<br />[其实链接现在很多都改成HTTPS了！](https://www.jianshu.com/notebooks/4128032/latest)
<br />[唉，为毛我看到上面说这样也行呢~][标识码是什么鬼？]:http://www.jianshu.com/notebooks/4128032/latest

---
|听说这样|可以|画表格？|
|-
|这闷热|的天气|终于外面下雨了
|是真的吗？|同事说|她要被吹飞走了😂|
|还是化成|蝴蝶|飞走😂

***笑尿~~~***

First Header | Second Header | Third Header
|
Content Cell | Content Cell  | Content Cell
Content Cell | Content Cell  | Content Cell


## [这是什么鬼？加粗的链接😂](http://www.jianshu.com/notebooks/4128032/latest)
[这样写能加粗么？貌似然并卵，难道说是页面内跳转？](#http://www.jianshu.com/notebooks/4128032/latest)

---

```
   		呀！Demo新技能啊！😂
   		可以可以
```
----
好吧，脚注这个有点麻烦呢.[^1]
[^1]:http://www.jianshu.com/notebooks/4128032/latest
***

Roses are red,   
Violets are blue.
<br />这是什么鬼功能哦~

---

> 这不只是一个引用

> > 这还是一个引用嵌套哦~

> #### 叫我内嵌大老粗😂，但是为毛我的斜体的
> 
> * 这是个列表
> * Etc.

---
1. 最少貌似要一个空格哦
2.  多加个空格呢？

---
* 点空一下 
<br />大哥让我挤挤😝
*  嘻嘻

---
* 点一下
	* tab点一下
* 嘛呢？
	1. 三分
	2. 抢地主
		* 小样
	3. 我抢
* 唉你呀的，闹呢！

---
Header 1
========
咋滴，不服？我就站这啦！
Header 2
--------

---
![alt text][id]

[id]: /url/to/img.jpg "Title"

![内嵌imaga啥玩意儿？](/url/to/img.jpg "这个可以不填")

---
他说这是一个email链接<qiGKnight@163.com>但是为毛不能转码一下 T.T

---
_下划线太难打了_
<br />__这个不好玩__

---
