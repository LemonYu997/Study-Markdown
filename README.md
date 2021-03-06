# Study-Markdown
# Markdown语法

## 一、标题

```java
//标题

# 一级标题			ctrl+1
## 二级标题			ctrl+2
### 三级标题		ctrl+3
#### 四级标题		ctrl+4
##### 五级标题		ctrl+5
###### 六级标题		ctrl+6
```



## 二、字体

```java
//加粗
**这是加粗字体**
//斜体
*这是斜体*
//删除线
~~这是删除线~~
//斜体加粗
***这是斜体加粗***
//脚注
真有趣[^这是脚注]
//高亮
==这是高亮==
//上标
这是^上标^
//下标   
这是~下标~
```

**这是加粗字体**

*这是斜体*

~~这是删除线~~

***这是斜体加粗***

真有趣[^这是脚注]

==这是高亮== 

这是^上标^

这是~下标~



## 三、引用

```java
>一级引用
>>二级引用
>>>三级引用
.........
```

>一级引用
>
>>二级引用
>>
>>>三级引用



## 四、分割线

```java
//以下几种语法分割线显示效果一样
---
----
***
****
```

---

----

***

****



## 五、图片

```java
//语法
![图片alt](图片地址"图片tittle")

//图片alt为图片下边的文字
//图片tittle为图片的标题，即鼠标移到图片上的内容
//图片地址 网址或者本地地址
```

![示例图片](https://ss0.bdstatic.com/70cFvHSh_Q1YnxGkpoWK1HF6hhy/it/u=702257389,1274025419&fm=27&gp=0.jpg "区块链")



## 六、超链接

```java
//语法
[超链接名](地址 "超链接tittle")

//示例
[Markdown图床](https://www.jianshu.com/p/ea1eb11db63f "必看！")
```

[Markdown图床](https://www.jianshu.com/p/ea1eb11db63f  "必看！")



## 七、列表

### 1、无序列表

```java
//语法
- 列表内容
+ 列表内容
* 列表内容

//中间要有空格，显示效果一样
```

- 列表内容

+ 列表内容

* 列表内容



### 2、有序列表

```java
//语法
1. 列表内容 
2. 列表内容
3. 列表内容

//中间有空格，英文符号句点
```

1. 列表内容 
2. 列表内容
3. 列表内容



### 3、列表嵌套

```java
//语法，下一级比上一级多三个空格
+ 列表内容
   + 列表内容
      + 列表内容
```



+ 列表内容
  + 列表内容
    + 列表内容

## 八、表格

```java
//语法
表头|表头|表头
---|:--:|---:
内容|内容|内容
内容|内容|内容

第二行分割表头和内容。
- 有一个就行，为了对齐，多加了几个
文字默认居左
-两边加：表示文字居中
-右边加：表示文字居右
注：原生的语法两边都要用 | 包起来。此处省略
```

| 表头 | 表头 | 表头 |
| ---- | :--: | ---: |
| 内容 | 内容 | 内容 |
| 内容 | 内容 | 内容 |



## 九、代码

### 1、单行代码

```java
//语法，用两个反引号包起来
`Hello World`
```



`Hello World`



### 2、多行代码

```java
//语法，三个反引号+语言
​```java
	Code
	Code
	Code
​```
```



```java
public class Test {
    public static void main(args[]) {
        System.out.println("Hello World");
    }
}
```



## 十、流程图

```java
//语法
​```flow
st=>start: 开始
op=>operation: My operation
cond=>condition: Yes or no?
e=>end
st->op->cond
cond(yes)->e
cond(no)->op
&```
```

```flow
st=>start: 开始
op=>operation: My operation
cond=>condition: Yes or no?
e=>end

st->op->cond
cond(yes)->e
cond(no)->op
&```
```