# HelloWorld
My first repository which name is HelloWorld, created on Aug 17th, 2018
## Program Language
C, C++, MATLAB, Python编程语言

***下面是md文件的书写练习***

# 标题书写练习
# 一级标题
## 二级标题
### 三级标题
#### 四级标题
##### 五级标题
###### 六级标题
一级标题
======
二级标题
------

# 字体格式
*强调*  (示例：斜体)  
 _强调_  (示例：斜体)  
**加重强调**  (示例：粗体)  
 __加重强调__ (示例：粗体)  
***特别强调*** (示例：粗斜体)  
___特别强调___  (示例：粗斜体)

# 文本
## 普通文本及换行
这是一行的起始，
直接回车不能换行，<br>
要使用\<br>或者\<br/><br>
在一行的末尾使用两个空格也可以换行<br>
这是一行，使用中文空格  
这是另一行，使用英文空格  
这是下一行
## 单行文本
使用两个Tab符实现单行文本,注意这里需要是英文输入法下的Tab

		这是一个单行文本

## 多行文本
在每行行首加两个Tab

		这是多行的第一行  
		这是多行的第二行  
		这是多行的第三行

## 多行文本2

	多行的第一行
	多行的第二行

## 多行文本3

多行的第一行<br>
多行的第二行,根据效果课件至少需要一个Tab

### 此处与代码框区别

```
这是多行的第一行  
这是多行的第二行  
这是多行的第三行
```

## 部分文字的高亮
如果想使部分文字高亮，突出强调，使用``包围即可，此符号不是单引号，是Tab上方，数字1左边的符号（注意使用英文输入法）<br/>
这是一段文字，我想让这个`字`高亮

## 文字超链接
### 行内式
格式是：\[要显示的文字\](链接的地址)<br>
[百度一下](https://www.baidu.com/)

### 参数式
格式是：\[name\]:链接地址 "注释说明".注意冒号后面加空格

[name1]: https://www.baidu.com/
[name2]: https://www.baidu.com/ "名字2"

这里是[name1]，这里是[name2]。

# 符号/列表
## 无序列表
使用\*,\+,\-后面加空格来创建，注意此处转义字符的使用

* 1
* 2
+ 3
+ 4
- 5
- 6

## 有序列表
使用正常的数字加一个.和空格表示。有序列表的序号有些解释器会根据第一行列表的数字顺序来递增的，还有一种会默认从1开始递增。  
1. 第一
2. 第二
3. 第三

## 转义字符
转义字符就是将特殊字符显示成正常显示的样子，大部分编程语言都使用反斜杠(\)表示  
* \\
* \`
* \*
* \!

## 分割线
分割线可以使用星号，减号，下划线这三个符号的至少三个符号表示，至少三个，不需连续，但两个符号之间至多一个空格,注意此处应该加一个空格

---
***
___

## 删除线
~~删除这里~~

# 代码块
代码量比较少，可以采用高亮的那种形式，用单反引号包起来<br>
`Hello World!`<br>
对于多行代码块可以使用\`\`\`进行标记，在后面可以写注释.<br>
```后面可以写注释
#include<iostream>

int main()
{
	std::cout << "Hello World!\n";
	return 0;
}
```

# 区块引用
使用\>表示，在后面加空格<br>
> 这是一个区块引用

> 这是另一个区块引用
>> 这是一个二级嵌套
>>> 这是一个三级嵌套

# 表格
建议在表格前空一行

| Name | Age | Sex |
|:----:|:----|----:|
| A    |  20 |  M男|
| B    |  18 |  F女|

注意上面:的位置表示的是对齐方式吗，分别表示居中，左对齐，右对齐。默认应该是左对齐

Name | Age | Sex
-----|-----|-----
A    | 20  | M
  B  | 18  | F

学号 | 姓名 | 分数
-|-|-
123| 小李 | 99
213| 小王 |98
321| 小郑 |97

# 图片引用
## 来源于网络的图片
![](https://www.baidu.com/img/dong_f6764cd1911fae7d460b25e31c7e342c.gif)

即使用\!\+方括号\[\]\+括号()，括号里面是图片的URL

![baidu](https://www.baidu.com/img/dong_f6764cd1911fae7d460b25e31c7e342c.gif)

（此处前面需要空格）此处添加的baidu文字不会引起改动<br>
如果需要鼠标悬停显示信息，需要添加文字说明

![](https://www.baidu.com/img/dong_f6764cd1911fae7d460b25e31c7e342c.gif "百度网页logo")

## Github仓库里的图片
与上面的格式基本一致，区别在于URL<br>
https://github.com/ 你的用户名 / 你的项目名 / raw / 分支名 / 存放图片的文件夹 / 该文件夹下的图片

![MFC](https://github.com/HaoHan1997/HelloWorld/raw/master/image/MFC.png)

## 给图片加超链接
[![baidu.png->baidu](https://github.com/HaoHan1997/HelloWorld/blob/master/image/baidu.png)](https://www.baidu.com/)
点击图片跳转到百度，此处是结合文字超链接和图片引用两个的引用方法结合起来写<br>
注意\[]括号里面的内容是在图片加载失败的时候显示

如果想改变图片的尺寸，可以通过代码标签
```
.<img src="https://github.com/Legend-yd/MyDawn/blob/master/20171223205540585.png" width="300" height="450" />
```

如果想改变图片居中
```
.<div align=center><img src="https://github.com/Legend-yd/MyDawn/blob/master/20171223205540585.png" width="300" height="450" /></div>
```








































