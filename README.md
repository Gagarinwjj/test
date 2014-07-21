TEST
===========================
This README.md is used to test all kinds of syntax of GitHub Flavored Markdown.
---------------------------
###　　　　　　　　　　　　Author:Jelly
###　　　　　　　　　 E-mail:wlyrics@163.com
###　　　　　　　　　　Modified:gagarinwjj
===========================



##<a name="index"/>目录
* [水平标尺](#line)
* [标题](#title)
* [文本](#text)
    * 无Tab 文本
    * Tab 单行文本
    * Tab 多行文本
* [代码](#code)
* [删除线](#strikethrough)
* [斜体和加粗](#italic)
* [文字链接](#link) 
    *  行内式
    *  参考式
    *  行内式 锚点 
* [图片链接](#pic)
    * 行内式 来源于网络的图片
    * 行内式 GitHub仓库中的图片
    * 参考式 [给图片加上超链接](#piclink)
* [列表](#dot)
* [引用](#symbol)
* [GFM代码块](#code)

<a name="line"/>
##***、---、___显示水平标尺

***
---
___



<a name="title"/>
#一级标题
##二级标题
###三级标题
####四级标题
#####五级标题
######六级标题


##<a name="text"/>文本
###无Tab的文本
这是一段普通的文本，  
直接回车不能换行，
要使用2个及以上的空格再回车。


###Tab 单行文本
    Hello,大家好，我是果冻虾仁。
###Tab 多行文本
    欢迎到访
    很高兴见到您
    祝您，早上好，中午好，下午好，晚安

##<a name="code">代码
Thank `You` . Please `Call` Me `Coder`

##<a name="strikethrough">删除线
这是一个 ~~删除线~~ ,GFM特有的。

##<a name="italic">斜体和加粗
*斜体1* **加粗2**

_斜体2_ __加粗2__

##<a name="link"/>文字链接
###行内式 
[我的博客](http://blog.csdn.net/guodongxiaren/article/details/23690801 "可选的悬停显示")
###参考式
[我的博客][myblog]
[myblog] http://www.cnblogs.com/gagarinwjj "我的博客园"
###行内式 锚点
[点此回到目录](#index)

##<a name="pic"/>图片链接
###行内式 外部URL
![baidu](http://www.baidu.com/img/bdlogo.gif "百度logo")
###行内式 GitHub仓库中的图片
![](https://github.com/guodongxiaren/ImageCache/raw/master/Logo/foryou.gif)
###<a name="piclink"> 给图片加上超链接
[![head]](http://blog.csdn.net/guodongxiaren/article/details/23690801)
[head]:https://github.com/guodongxiaren/ImageCache/raw/master/Logo/jianxin.jpg "点击图片进入我的博客"

##<a name="dot"/>列表
###圆点列表
* 昵称：果冻虾仁
* 别名：隔壁老王
* 英文名：Jelly

###更多圆点
* 编程语言
    * 脚本语言
        * Python

### 复选框列表，GFM特有
- [x] C
- [x] C++
- [x] Java
- [x] Qt
- [x] Android
- [ ] C#
- [ ] .NET

##<a name="symbol"/>引用
###嵌套引用
>数据结构
>>树
>>>二叉树
>>>>平衡二叉树
>>>>>满二叉树

###非嵌套引用
####文本摘自《深入理解计算机系统》P27
　令人吃惊的是，在哪种字节顺序是合适的这个问题上，人们表现得非常情绪化。实际上术语“little endian”（小端）和“big endian”（大端）出自Jonathan Swift的《格利佛游记》一书，其中交战的两个派别无法就应该从哪一端打开一个半熟的鸡蛋达成一致。因此，争论沦为关于社会政治的争论。只要选择了一种规则并且始终如一的坚持，其实对于哪种字节排序的选择都是任意的。
><b>“端”（endian）的起源</b>  
以下是Jonathan Swift在1726年关于大小端之争历史的描述：  
“……下面我要告诉你的是，Lilliput和Blefuscu这两大强国在过去36个月里一直在苦战。战争开始是由于以下的原因：我们大家都认为，吃鸡蛋前，原始的方法是打破鸡蛋较大的一端，可是当今的皇帝的祖父小时候吃鸡蛋，一次按古法打鸡蛋时碰巧将一个手指弄破了，因此他的父亲，当时的皇帝，就下了一道敕令，命令全体臣民吃鸡蛋时打破较小的一端，违令者重罚。”


##<a name="code"/>GFM代码块
```Java
public static void main(String[]args){} //Java
```
```c
int main(int argc, char *argv[]) //C
```
```Bash
echo "hello GitHub"#Bash
```
```javascript
document.getElementById("myH1").innerHTML="Welcome to my Homepage"; //javascipt
```
```cpp
string &operator+(const string& A,const string& B) //cpp
```
##表格
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| First Header  | Second Header |
| ------------- | ------------- |
| Content Cell  | Content Cell  |
| Content Cell  | Content Cell  |

| Name | Description          |
| ------------- | ----------- |
| Help      | Display the help window.|
| Close     | Closes a window     |

| Name | Description          |
| ------------- | ----------- |
| Help      | ~~Display the~~ help window.|
| Close     | _Closes_ a window     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |
