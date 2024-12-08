---
date: '2024-12-08T15:56:44+08:00'
draft: false 
title: '测试'
---

🚧 桶装幺蛾子的新版本即将上线 🚧

旧网站位于 [OLD](https://old.dumpster.top)。

这个页面对 Hugo、PaperMod 和本蛾子自己的配置的 Markdown 语法显示效果进行测试。

参考 [iHaPBoy 的 Gist](https://gist.github.com/iHaPBoy/a7d1c4f9ccf180c43b696a0a7c9d5381) 并整理、剔除了部分过于怪异的语法，仅测试标准。

## 换行

**不应当换行**

1
2
3

**应当同段换行**

a  
b

**分割线**

---

## 链接

**链接**

[Arch Linux](https://archlinux.org)

**图片**

![](https://archlinux.org/static/archnavbar/archlogo.8a05bc7f6cd1.svg)

**视频**

<iframe src="//player.bilibili.com/player.html?isOutside=true&aid=1706416465&bvid=BV1UT42167xb&cid=1641702404&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"></iframe>

## 标题

**标题**

# H1

## H2

### H3

#### H4

##### H5

###### H6

### 嵌套[链接](https://archlinux.org)和***效果***

**目录（Hugo 语法）**

{{ .TableOfContents }}

## 效果

**字符**

~~删除~~

*斜体*

**粗体**

***粗斜体***

**HTML 效果**

X<sub>2</sub>

O<sup>2</sup>

<center>居中</center>

## 引用

> 引用文本

角标[^1]

[^1]: Aloha!

## 代码

**行内**

执行命令：`hugo new site mysite`

**多行**

```rust
fn main() {
    println!("Hello, world!");
}
```

**缩进实现**

    <?php
        echo "Hello world!";
    ?>
    
**消歧义**

    | First Header  | Second Header |
    | ------------- | ------------- |
    | Content Cell  | Content Cell  |
    | Content Cell  | Content Cell  |

## 列表

**无序**
                
- 1
- 2
- 3

**无序换行**

- 1  
 同行文字
- 2

**无序嵌套**

- 1
  - 1.1
  -1.2
- 2

**有序**
                
1. 第一行
2. 第二行
3. 第三行

**任务清单**

- [x] GFM task list 1
- [x] GFM task list 2
- [ ] GFM task list 3
    - [ ] GFM task list 3-1
    - [ ] GFM task list 3-2
    - [ ] GFM task list 3-3
- [ ] GFM task list 4
    - [ ] GFM task list 4-1
    - [ ] GFM task list 4-2
                    
**表格**

| 项目        | 价格   |  数量  |
| --------   | -----:  | :----:  |
| 计算机      | $1600   |   5     |
| 手机        |   $12   |   12   |
| 管线        |    $1    |  234  |
                    
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell 

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Function name | Description                    |
| ------------- | ------------------------------ |
| `help()`      | Display the help window.       |
| `destroy()`   | **Destroy your computer!**     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

| Item      | Value |
| --------- | -----:|
| Computer  | $1600 |
| Phone     |   $12 |
| Pipe      |    $1 |

## HTML 符号

&copy; &  &uml; &trade; &iexcl; &pound;
&amp; &lt; &gt; &yen; &euro; &reg; &plusmn; &para; &sect; &brvbar; &macr; &laquo; &middot; 

X&sup2; Y&sup3; &frac34; &frac14;  &times;  &divide;   &raquo;

18&ordm;C  &quot;  &apos;
 
## 反斜杠

\*真正的星号\*

\`\`\` 真正的反引号
            
## 公式

**行内公式**

$E=mc^2$

$\sqrt{3x-1}+(1+x)^2$
                    
$\sin(\alpha)^{\theta}=\sum_{i=0}^{n}(x^i + \cos(f))$

**多行公式**

$$
\displaystyle
\left( \sum_{k=1}^n a_k b_k \right)^2
\leq
\left( \sum_{k=1}^n a_k^2 \right)
\left( \sum_{k=1}^n b_k^2 \right)
$$

$$
\displaystyle 
    \frac{1}{
        \Bigl(\sqrt{\phi \sqrt{5}}-\phi\Bigr) e^{
        \frac25 \pi}} = 1+\frac{e^{-2\pi}} {1+\frac{e^{-4\pi}} {
        1+\frac{e^{-6\pi}}
        {1+\frac{e^{-8\pi}}
         {1+\cdots} }
        } 
    }
$$

$$
f(x) = \int_{-\infty}^\infty
    \hat f(\xi)\,e^{2 \pi i \xi x}
    \,d\xi
$$
