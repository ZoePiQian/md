请阅读下方文本熟悉工具使用方法，本文可直接拷贝到微信中预览。

## 1 Rabbit 微信编辑器简介

- 支持自定义样式的 Markdown 编辑器
- 支持微信公众号、知乎一键复制

## 2 主题

**https://输入兔兔的域名/**

>>欢迎访问 Rabbit Hole 网站

## 3 通用语法

### 3.1 标题

在文字写书写不同数量的`#`可以完成不同的标题，如下：

# 一级标题

## 二级标题

### 三级标题

### 3.2 无序列表

无序列表的使用，在符号`-`后加空格使用。如下：

- 无序列表 1
- 无序列表 2
- 无序列表 3

如果要控制列表的层级，则需要在符号`-`前使用空格。如下：

- 无序列表 1
- 无序列表 2
  - 无序列表 2.1
  - 无序列表 2.2

**由于微信原因，最多支持到二级列表**。

### 3.3 有序列表

有序列表的使用，在数字及符号`.`后加空格后输入内容，如下：

1. 有序列表 1
2. 有序列表 2
3. 有序列表 3

### 3.4 粗体和斜体

粗体的使用是在需要加粗的文字前后各加两个`*`。

而斜体的使用则是在需要斜体的文字前后各加一个`*`。

如果要使用粗体和斜体，那么就是在需要操作的文字前后加三个`*`。如下：

**这个是粗体**

_这个是斜体_

**_这个是粗体加斜体_**

注：由于 commonmark 标准，可能会导致加粗与想象不一致，如下

### 3.5 链接

微信公众号仅支持公众号文章链接，即域名为`https://mp.weixin.qq.com/`的合法链接。使用方法如下所示：

对于该论述，欢迎读者查阅之前发过的文章，[好心仙子的故事](https://mp.weixin.qq.com/s/kfX11YytuuxWtj-quPCP3w)

### 3.6 引用

引用的格式是在符号 `>` 后面书写文字，文字的内容可以包含标题、链接、图片、粗体和斜体等。

一级引用如下：

> ### 一级引用示例
> 
> 人生是一场自我实现的预言。 **——欧文·亚隆**

当使用多个 `>` 符号时，就会变成多级引用

二级引用如下：

>> ### 二级引用示例
>>
>> 希望派派从城堡的窗户向外看去，海面上总有一艘船，闪闪灯火。 **——鲸鱼**


### 3.7 分割线

可以在一行中用三个以上的减号来建立一个分隔线，同时需要在分隔线的上面空一行。如下：

---

### 3.8 删除线

删除线的使用，在需要删除的文字前后各使用两个`~`，如下：

~~这是要被删除的内容。~~

### 3.9 表格

可以使用冒号来定义表格的对齐方式，如下：

| 姓名       | 年龄 |         工作 |
| :--------- | :--: | -----------: |
| 波粒二象性     |  8个月  |     咬电线 |
| 小黑猫   |  10岁  |   欺负小白猫 |
| 小白猫   | 10岁   | 欺负兔兔 |

### 3.10 图片

- 支持图片**拖拽和截图粘贴**到编辑器中上传，上传时使用当前选择的图床。

**注：仅支持 https 的图片，图片粘贴到微信、知乎或掘金时会自动上传其服务器，不必担心使用上述图床会导致图片丢失**。


## 4. 特殊语法

### 4.1 脚注

> 脚注与链接的区别如下所示：

```markdown
链接：[文字](链接)
脚注：[文字](脚注解释 "脚注名字")
```

[商业内观](https://if.zoepi.online)是一份线上电子杂志。

[商业内观](穿梭在人类用思维模型构建的商业世界里，却时常想摆渡回到「轴心时代」的宇宙空间站。 "什么是商业内观？")不定期更新，欢迎[订阅](https://rss.zoepi.online)。

脚注内容请拉到最下面观看。

### 4.2 代码块

> 支持平台：微信公众号、知乎。

如果在一个行内需要引用代码，只要用反引号引起来就好，如下：

Use the `printf()` function.

在需要高亮的代码块的前一行及后一行使用三个反引号，同时**第一行反引号后面表示代码块所使用的语言**，如下：

```java
// FileName: HelloWorld.java
public class HelloWorld {
  // Java 入口程序，程序从此入口
  public static void main(String[] args) {
    System.out.println("Hello,World!"); // 向控制台打印一条语句
  }
}
```
## Welcome to Rabbit Hole
