# 一级标语（全文标语），只能出现一次

## 二级标语

### 三级标语

#### 四级标语（和普通文字差不多大）

##### 五级标语

###### 六级标语

---
公共的特性：  
行内文字加2个空格，即会换行显示  
markdown的标签需要使用\字符来转义，才能显示出来

---

## 强调（Emphasis）

*倾斜文字，md行内标签之间加2个空格会换行显示*  
_倾斜文字_  
**加粗文字**  
__加粗文字__  
_综合使用斜体文字和**加粗文字**_  

---

## 列表（List）

### 无序列表（unordered）

* item1
* item2
  * item2.1
  * item2.2

### 有序列表（ordered）

1. item1
1. item2
   1. item2.1
   1. item2.2

## 图片（images）

图片的使用方法1：资源地址很长，影响美观了。  
![这是图片说明文字](https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1551587216893&di=c27a195d2e707c4b9fa185dce4d30236&imgtype=0&src=http%3A%2F%2Ftn04.v.sogou.com%2Faca20264578a71a2-b9f42f71826112e0_i.jpg)

图片的使用方法2：使用别名，需要在下面定义  
![这是图片的说明文字][girl]

[girl]:https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1551587216893&di=c27a195d2e707c4b9fa185dce4d30236&imgtype=0&src=http%3A%2F%2Ftn04.v.sogou.com%2Faca20264578a71a2-b9f42f71826112e0_i.jpg

(github上Format这条没搞懂)

## 链接(Links)

http://github.com  
[链接文字](http://github.com)

## 引用(Blockquotes)

> 这是被引用的文字  
> 也是行内属性的，需要换行打2空格

## 行内代码

文本中嵌入一点代码 `<div>` 也是可以的