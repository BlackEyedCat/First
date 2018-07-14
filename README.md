# 《甲》练习使用标题
## 一、atx风格二级标题（1、#后面有一个空格，2、n个#即为n级标题，3、最多六个#）
## 二、atx风格标题可以以‘#'进行结束,只是为了美观，不限数量 #####
三、setext风格一级标题（在标题内容下一行为单纯的等号，有一个便足够）
=================
四、setext风格二级标题（在标题内容下一行为单纯的连字符，有一个便足够）
----------------


# 《乙》练习使用引用块
>一、符号>制造引用块
>二、n个>制造n级引用块
>三、引用块符号‘>’后面不需要空格
>>四、当>数量达到突破时会形成相应级数的引用块（二级>>）
>>>>>五、引用块的级数可以跳级（>>>>>）
>六'>'数量没有实现突破，则该行引用与上一行连接，相隔一个空格（相对于>>>>>是无、>、>>、>>>、>>>>、>>>>>）
>七任意多个>+空白行可以实现换行，换行之后最大级数归零可以重新嵌套（如下>>>>>>>+空）
>>>>>>>>
>>二级引用
>八\无>+空白行可以实现无引用块换行，换行之后最大级数归零可以重新嵌套（ 如下）

>>二级引用
>### 九、引用块中可以用标题、列表、代码块等

# 《丙》练习使用列表
*  一、‘*’无序列表。
+  二、‘+’无序列表。
-  三、‘-’无序列表。 四、-‘-’无序列表-->无序列表必须换行。
*五、‘+’‘-’‘*’后必须有空格，否则计入上一行列表。

* 六、空行无效果。
15.  一、‘数字.’是有序列表。
2.  二、有序列表的第一个数字是起始序号，后续的其他数字只是延续的作用，没有标记序号的作用。 3. 三、‘3.有序列表’-->有序列表必须换行。

99. 四、空行无效果。
109.五、‘数字.’后必须有空格，否则计入上一行列表。

 * 列表前有一个空格：空格不显示，也没有破坏列表。
 * 列表前有缩进，回车会保持缩进。
*  符号后2空格
*   符号后3空格
*    符号后4空格
*     符号后5空格
*      6
*        7
* 符号后1tab
*   2
*     3
*       4
*         5
*    1空格1tab1空格
*     1空格2tab
* 符号后至少有一个空格或一个tab，且效果相同；开头tab相对于一个空格，其他为2个；符号后4个以及以内的空格与一个空格效果相同，多于四个会有上面的效果。
* 00000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
一、换行位置（编辑框内换行位置不是显示框内的换行位置，会在换行位置进行衔接，所以即使没到一行末尾进行换行也会被衔接，同样的如果在一个列表中有多个段落也会被衔接）二、编辑框内两行文字没有对齐，但在显示框中是对齐的 三、换行仍然是同一列表00000000000000
*   000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000000
    第一行一空格一tab，第二行2tab0000000，没有显示效果，只在编辑框内美化
* 01

    02在一个链表中表示多个段落：1、换段落先空一行，否则连成一行 2、后续段落的第一行至少缩进四个空格或一个tab，否则变成正文。
*  引用01
   >引用02
   >>引用03
      >>>引用04每行的引用必须与列表的第一行缩进到至少同一位置至多后置2个空格才会被放进列表中。
* 在列表项中使用代码块，代码块需要缩进两次 -- 8个空格或者两个TAB
* 以数字＋句点＋空格 序列起始的行会触发有序列表。为避免此情况，要对句点符号进行转义：'\.' 。

# 《丁》代码块
    1.缩进至少四个空格或一个tab
    2.代码块中的markdown元素不再解释，如：
    * 不是列表。
    3.代码块的效果就是这种浅色框
    4.在列表中也可以使用代码块，上面出现过，只要在*/-/+/1.的后面缩进至少5个空格，入下：
*    4个
*     5个

# 《戊》水平线
/>=三个连字符：(水平线与二级标题使用连字符的区别在于1.数量：前者>=3,后者，没有限值 2.前者不能连续，后者必须连续（只有一个的话就是标题）)
- - -
/>=三个星号：
***
/>=三个下划线：
___

# 《己》链接
[链接1的显示](http://www.ituring.com.cn/article/775 "接触时的显示 图灵社区")
1. 显式文本放在【】中，链接放在（）中，隐式文本放在（""）中，形式为：【显式文本】(链接 “隐式文本”)，要用英文标点，链接与“”之间必须有空格，否则效果如下：
[链接1的显示](http://www.ituring.com.cn/article/775"接触时的显示 图灵社区")
上面也说明可以直接放链接。
2. [链接二的显示:引用一个本地资源或者同一站点的资源，可以使用相对路径](/README.md "隐式")
3.    声明：[foo]: http://example.com/  "Optional Title Here" 行前不超过三个空格，【】后紧跟‘：’，‘：’后任意数空格，标识符不区分大小写
       [foo]: http://example.com/  'Optional Title Here'
       [foo]: http://example.com/  (Optional Title Here)
       [id]: <http://example.com/>  "Optional Title Here"
[A]:http://www.ituring.com.cn/article/775  "隐" 
[链接三的显示][a]
4.  [隐式链接、冒号不可以是中文、名字可以有空格][]

[隐式链接、冒号不可以是中文、名字可以有空格]: http://www.ituring.com.cn/article/775 "隐文"

# 《庚》强调
*星、文字、星强调*是斜体
_下划线、文字、下划线强调_ 是斜体

**双星、文字、双星强调**是粗体
__2个下划线、文字、两个下划线强调__ 是粗体

**强**调 _可以_ 用在*句子*中间
包裹空格失去意义* *
*只有一端的符号，在编辑框中除非空一行，否则
强调不会结束，但是在显示框中不会显示为强调。

一个或两个下划线的强调首位必须没有文本，要么是行首、尾，要么用空格，否则没有强调，如下：_bushiqinagdiao_。
转移字符\*111\*

# 《辛》代码
这里是一个代码`一对反引号包裹住代码，可以用于行内`。
在行内代码中``使用`一定数量连续的反引号`要用数量更多连续的反引号做边界符``，下面是五包三`````huhu```hu```hu`````
起始定界符之后、结束定界符之前紧跟着就要用到反引号时，可以用空格隔开，可以这样做的原因是定界符可以用空格隔开，如下`` `左侧尝试一个空格ha空格数量不限ha不显示空格ha右侧尝试10个空格`          ``

# 《壬》图片
* ![Alt text](/path/to/img.jpg "Optional title")
一个感叹号!开头；
其后紧跟一对中括号，中括号内存放图片的alt`属性；
其后紧跟一对小括号，小括号内存放图片的URL或路径，及可选的用双引号或单引号或小括号括起来的图片title
* ![Alt text][id]
[id]: url/to/image  "Optional title attribute"

# 《癸》其他
1.  自动连接
<http://www.ituring.com.cn/article/775>
直接用一对尖括号把URL或Email地址包住
2.      反斜线转义
        \   反斜线
        \`   反引号
       \ *   星号
       \_   下划线
       \{}  大括号
      \ []  中括号
      \()  小括号
      \#   井号
       \+   加号
       \-   减号（连字符）
       \.   句点
       \!   感叹号
