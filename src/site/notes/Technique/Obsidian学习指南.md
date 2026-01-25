---
{"dg-publish":true,"dg-K":true,"tags":["obsidian","latex"],"authors":"Fish","DAY":"2026-01-25","permalink":"/Technique/Obsidian学习指南/","dgPassFrontmatter":true,"created":"2026-01-25T09:51:40.695+08:00","updated":"2026-01-25T12:11:06.946+08:00"}
---

## 附件
- 添加附件的方法
	- 复制粘贴附件
	- 拖放附件
	- 将附件下载到仓库
<iframe src="/img/user/STudy%20Plan/%E4%BA%BA%E5%B7%A5%E6%99%BA%E8%83%BD%E4%B8%93%E4%B8%9A%E5%9F%B9%E5%85%BB%E6%96%B9%E6%A1%88.pdf" width="100%" height="900px" title="人工智能专业培养方案.pdf" style="border:1px solid #ccc;"></iframe>

## 数学公式

$$
a_0 [x] (x) \frac{a}{b} \sqrt[n]{a+b}

\sum_{i=0}^{n}\frac{1}{i^2}
$$
$$ \prod_{i = 0}^{n}\frac{1}{x2} $$
$$ \sin$$
$$ \bot$$
$$ \ln{(a+b)}$$ $$ \pm$$ $\frac{123}{999}$、$\sqrt[n]{abc}$、$\frac{\sqrt{234}}{\sqrt[n]{abc}}$、$\underrightarrow{abc}$、$\overrightarrow{abc}$
$$
 \int_0^{+\infty}f(x)\,dx
$$

$$
 \begin{vmatrix}
 0&1&2\\
 3&4&5\\
 6&7&8\\
 \end{vmatrix}
 $$
$$
\begin{bmatrix}已知y=\sqrt{x+3}&&(x>=0)\\求y的最大值是多少 \end{bmatrix}
$$
$$
\begin{aligned}a=b+c\\b=c-a\\c=a+b \end{aligned}
$$
$E=mc^2$
$\sin$
sad $\cos(6)$
$$
Let $f\colon[a,b]\to\R$ be Riemann integrable. Let $F\colon[a,b]\to\R$ be
$F(x)=\int_{a}^{x} f(t)\,dt$. Then $F$ is continuous, and at all $x$ such that
$f$ is continuous at $x$, $F$ is differentiable at $x$ with $F'(x)=f(x)$.
$$

## 标注

1. 创建引用块
2. 第一行添加`[!info]`即可
3. 示例
> [!info]
> 这是一个标注块
> 它支持**markdown**，[[STudy Plan/Fruit的大一秋冬的学业分享与总结\|Fruit的大一秋冬的学业分享与总结]]

 > [!faq]+ 标注可以折叠吗？
> 	可以！在可折叠标注中，当标注收起时，内容会被隐藏。
> [!question] 标注可以嵌套吗？
> > [!todo] 可以。
> > > [!example]  你甚至可以使用多层嵌套。

4. 其他标注
	- question / faq / help
	- Warning / caution / attention 
	- Failure / fail
	- Danger / error
	- Bug
	- Example
	- Quote / cite
	- Tip
	- Success
	- Todo
	- Abstract
	- Note
	- Info
	- 

## 嵌入网页

1. 嵌入网页	
<iframe src="[还在用Word写毕设？喂饭级教程带你上手Latex！从零开始打造最优雅的写作方式 - CC98论坛](https://www.cc98.org/topic/6353479))"></iframe>

2. 嵌入视频
<div class="youtube-embed"><iframe src="https://www.youtube.com/embed/KGd-2tcNbiU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>
<div class="youtube-embed"><iframe src="https://www.youtube.com/embed/NnTvZWp5Q7o" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe></div>

## 基本格式语法

- 段落
	- 空行分隔
	- 
	  ```
	  第一行
	  
	  第二行
	  ```
	- 多个空格 &nbsp
	- 多个空行 <br>
- 加粗 **s**
- 斜体 *s*
- 删除线 ~~s~~
- 高亮 ==s==
- 粗体加斜体 ***s***
- 转义字符 \*s*\**s**

- list
	- 嵌套列表
		- 缩进
		- 取消缩进 `shift+Tab`即可
	- 任务列表
- [x] 写作业
- [ ] ⏳ 2026-01-26 🔼 ⛔ 看电影
- [ ] 写作业
- [ ] 看电影🔺 

- 水平线

- 行内代码

- 代码块

- 脚注

- 注释（只在编辑视图中可见）
	- 

- 链接
	- 内部链接
		- [[English/NCE4\|NCE4]]
	- 外部链接
		- [obsidian help](https://help.obsidian.md)
	- 外部图片
		- 外部链接前面加上`!`符号
		- ![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
		- ```
		  ![Engelbart](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
		  ```
		- 图片大小改变
			- ![Engelbart|100x145](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
			- ```
			  ![Engelbart|100x145](https://history-computer.com/ModernComputer/Basis/images/Engelbart.jpg)
			  ```
	

- 引用
	> abcd


- 小标题
	- 
	```
	# 这是标题 1
	## 这是标题 2
	### 这是标题 3
	#### 这是标题 4
	##### 这是标题 5
	###### 这是标题 6 ```
	