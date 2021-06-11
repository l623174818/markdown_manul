# **Markdown**

## 0 Markdown 前言

- 微信公众号排版工具。问题或建议，请公众号留言。***[程序员翻身](#jump_8)***  
- 建议使用 **Chrome** 浏览器，体验最佳效果。  
- 使用微信公众号编辑器有一个十分头疼的问题：粘贴出来的代码，格式错乱，空间小还带行号，而且特别Markdown编辑器能够解决这个问题。  
- Markdown是一种轻量级的「标记语言」。  
- 请阅读下方文本熟悉工具使用方法，本文可直接拷贝到微信中预览。  

## 1 Markdown 简介

- 支持自定义样式的 Markdown 编辑器
- 支持微信公众号、知乎和稀土掘金
- 点击右上方对应图标，一键复制到各平台

## 2 Markdown语法教程  

### 2.1 标题  

不同数量的`#`可以完成不同的标题，如下：  

> # 一级标题

```markdown
# 一级标题 
一级标题
=========================
```

> ## 二级标题

```markdown
## 二级标题 
二级标题
-------------------------
```

> ### 三级标题
>
> #### 四级标题
>
> ##### 五级标题
>
> ###### 六级标题

```markdown
### 三级标题  
#### 四级标题 
##### 五级标题
###### 六级标题  
```

### 2.2 字体

粗体、斜体、粗体和斜体，删除线，需要在文字前后加不同的标记符号。如下：

> *这个是斜体*  

```markdown
*这个是斜体*  
```

> **这个是粗体**  

```markdown
**这个是粗体**
```

> ***这个是粗体加斜体***  

```markdown
    ***这个是粗体加斜体***
```

> ~~这里想用删除线~~  

```markdown
    ~~这里想用删除线~~
```

*注：如果想给字体换颜色、字体或者居中显示，需要使用内嵌HTML来实现。*

### 2.3 无序列表

无序列表的使用，在符号`-`后加空格使用。如下：

> - 无序列表 1
> - 无序列表 2
> - 无序列表 3

```markdown
- 无序列表 1
- 无序列表 2
- 无序列表 3
```

如果要控制列表的层级，则需要在符号`-`前使用空格。如下：

> - 无序列表 1
> - 无序列表 2
>   - 无序列表 2.1
>   - 无序列表 2.2  

```markdown
- 无序列表 1
- 无序列表 2
    - 无序列表 2.1
    - 无序列表 2.2  
```

*注：由于微信原因，最多支持到二级列表。*

### 2.4 有序列表

有序列表的使用，在数字及符号`.`后加空格后输入内容，如下：

> 1. 有序列表 1
> 2. 有序列表 2
> 3. 有序列表 3

```markdown
1. 有序列表 1
2. 有序列表 2
3. 有序列表 3
```

### 2.5 引用

引用的格式是在符号`>`后面书写文字。如下：

> 读一本好书，就是在和高尚的人谈话。 ——歌德
>
> 雇用制度对工人不利，但工人根本无力摆脱这个制度。 ——阮一峰  

```markdown
> 读一本好书，就是在和高尚的人谈话。 ——歌德
>
> 雇用制度对工人不利，但工人根本无力摆脱这个制度。 ——阮一峰  
```

### 2.7 链接

微信公众号仅支持公众号文章链接，即域名为<https://mp.weixin.qq.com/>的合法链接。使用方法如下：

> [你是《未来世界的幸存者》么？](https://mp.weixin.qq.com/s/s5IhxV2ooX3JN_X416nidA)

```markdown
  [你是《未来世界的幸存者》么？](https://mp.weixin.qq.com/s/s5IhxV2ooX3JN_X416nidA)  
```

### 2.8 图片

插入图片，支持 jpg、png、gif、svg 等图片格式，如下：

> ![这里写图片描述](https://www.nginx.cn/wp-content/uploads/2020/03/qrcode_for_gh_82cf87d482f0_258.jpg)

```markdown
![这里写图片描述](https://www.nginx.cn/wp-content/uploads/2020/03/qrcode_for_gh_82cf87d482f0_258.jpg)
```

*注：*

1. *其中 svg 文件仅可在微信公众平台中使用。*
2. *支持图片 ***拖拽和截图粘贴*** 到编辑器中，仅支持 https 的图片，图片粘贴到微信时会自动上传微信服务器。*  

### 2.9 分割线

可以在一行中用三个以上的减号来建立一个分隔线，同时需要在分隔线的上面空一行。如下：

> 分割线
> ***

```markdown
分割线
***
```

### 2.10 表格

可以使用冒号来定义表格的对齐方式，如下：

> | 姓名 | 年龄 | 工作 |
> | :- | :-: | -: |
> | :左 | :中: | 右: |
> | 小可爱 | 18 | 吃可爱多 |
> | 小小勇敢 | 20 | 爬棵勇敢树 |
> | 小小小机智 | 22 | 看一本机智书 |

```markdown
| 姓名        | 年龄  |         工作 |
| :--------- | :---: | -----------: |
| :左        | :中:  |          右: |
| 小可爱     |  18   |     吃可爱多 |
| 小小勇敢   |  20   |   爬棵勇敢树 |
| 小小小机智 |  22   | 看一本机智书 |
```

## 3. 特殊语法

### 3.1 脚注

脚注如下所示：

> [全栈工程师](是指掌握多种技能，并能利用多种技能独立完成产品的人。 "什么是全栈工程师")在业务开发流程中起到了至关重要的作用。

```markdown
[全栈工程师](是指掌握多种技能，并能利用多种技能独立完成产品的人。 "什么是全栈工程师")在业务开发流程中起到了至关重要的作用。
```

链接如下所示：

> 有人认为在[大前端时代](https://en.wikipedia.org/wiki/Front-end_web_development "Front-end web development")的背景下，移动端开发（Android、IOS）将逐步退出历史舞台。

```markdown
有人认为在[大前端时代](https://en.wikipedia.org/wiki/Front-end_web_development "Front-end web development")的背景下，移动端开发（Android、IOS）将逐步退出历史舞台。  
```

*注：支持平台：微信公众号、知乎。脚注内容请拉到最下面观看。*

### 3.2 代码块

如果在一个行内需要引用代码，只要用反引号引起来就好，如下：

> Use the `printf()` function.

```markdown
Use the `printf()` function.
```

如果在多行内需要引用代码，前一行及后一行使用三个反引号，第一行反引号后面表示代码块所使用的语言，如下：

> ```java
> // FileName: HelloWorld.java
> public class HelloWorld {
>   // Java 入口程序，程序从此入口
>   public static void main(String[] args) {
>     System.out.println("Hello,World!"); // 向控制台打印一条语句
>   }
> }
> ```

    ```java
    // FileName: HelloWorld.java
    public class HelloWorld {
      // Java 入口程序，程序从此入口
      public static void main(String[] args) {
        System.out.println("Hello,World!"); // 向控制台打印一条语句
      }
    }  
    ```

*注：支持以下语言种类：*

1. bash  
2. clojure，cpp，cs，css  
3. dart，dockerfile, diff  
4. erlang  
5. go，gradle，groovy
6. haskell
7. java，javascript，json，julia
8. kotlin
9. lisp，lua
10. makefile，markdown，matlab
11. objectivec
12. perl，php，python
13. r，ruby，rust
14. scala，shell，sql，swift
15. tex，typescript
16. verilog，vhdl
17. xml
18. yaml

### 3.3 数学公式(微信公众号、知乎)

行内公式使用方法，比如这个化学公式：

> $\ce{Hg^2+ ->[I-] HgI2 ->[I-] [Hg^{II}I4]^2-}$

```markdown
$\ce{Hg^2+ ->[I-] HgI2 ->[I-] [Hg^{II}I4]^2-}$
```

块公式使用方法如下：

> $$H(D_2) = -\left(\frac{2}{4}\log_2 \frac{2}{4} + \frac{2}{4}\log_2 \frac{2}{4}\right) = 1$$

```markdown
$$H(D_2) = -\left(\frac{2}{4}\log_2 \frac{2}{4} + \frac{2}{4}\log_2 \frac{2}{4}\right) = 1$$
```

矩阵：

> $$
>   \begin{pmatrix}
>   1 & a_1 & a_1^2 & \cdots & a_1^n \\
>   1 & a_2 & a_2^2 & \cdots & a_2^n \\
>   \vdots & \vdots & \vdots & \ddots & \vdots \\
>   1 & a_m & a_m^2 & \cdots & a_m^n \\
>   \end{pmatrix}
> $$

```markdown
$$
  \begin{pmatrix}
  1 & a_1 & a_1^2 & \cdots & a_1^n \\
  1 & a_2 & a_2^2 & \cdots & a_2^n \\
  \vdots & \vdots & \vdots & \ddots & \vdots \\
  1 & a_m & a_m^2 & \cdots & a_m^n \\
  \end{pmatrix}
$$
```

*注：*

1. *公式由于微信不支持，目前的解决方案是转成 svg 放到微信中，无需调整，矢量不失真。*
2. *目前测试如果公式量过大，在 Chrome 下会存在粘贴后无响应，但是在 Firefox 中始终能够成功。*

### 3.4 TOC(微信公众号、知乎)

TOC 全称为 Table of Content，列出全部标题。

> [TOC]

```markdown
[TOC]
```

*注：由于微信只支持到二级列表，本工具仅支持二级标题和三级标题的显示。*

### 3.5 注音符号(微信公众号)

支持注音符号，用法如下：

> Markdown Nice 这么好用，简直是{喜大普奔|hē hē hē hē}呀！

```markdown
Markdown Nice 这么好用，简直是{喜大普奔|hē hē hē hē}呀！
```

### 3.6 横屏滑动幻灯片(微信公众号)

通过`<![](url),![](url)>`这种语法设置横屏滑动滑动片，具体用法如下：

> <![蓝1](https://www.nginx.cn/wp-content/uploads/2020/03/qrcode_for_gh_82cf87d482f0_258.jpg),![绿2](https://www.nginx.cn/wp-content/uploads/2020/03/qrcode_for_gh_82cf87d482f0_258.jpg),![红3](https://www.nginx.cn/wp-content/uploads/2020/03/qrcode_for_gh_82cf87d482f0_258.jpg)>

```markdown
<![蓝1](https://my-wechat.mdnice.com/mdnice/%E8%93%9D1_20191109174052.jpg),![绿2](https://my-wechat.mdnice.com/mdnice/%E7%BB%BF2_20191109174052.jpg),![红3](https://my-wechat.mdnice.com/mdnice/%E7%BA%A23_20191109174052.jpg)>
```

## 4 其他语法

### 4.1 HTML

支持原生 HTML 语法，请写内联样式，如下：

> <span style="display:block;text-align:right;color:orangered;">橙色居右</span>
> <span style="display:block;text-align:center;color:orangered;">橙色居中</span>

```markdown
<span style="display:block;text-align:right;color:orangered;">橙色居右</span>
<span style="display:block;text-align:center;color:orangered;">橙色居中</span>
```

### 4.2 UML

不支持，推荐使用开源工具`https://draw.io/`制作后再导入图片

## 5 致谢

- 编程如画 [markdown-nice-docs](https://github.com/mdnice/markdown-nice "插件原作者")
- 歌词经理 [wechat-fromat](https://github.com/lyricat/wechat-format "灵感来源")
- 颜家大少 [MD2All](http://md.aclickall.com/ "MdA2All")
