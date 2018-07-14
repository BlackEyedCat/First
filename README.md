# [甲]练习使用标题
## 一、atx风格二级标题（1、#后面有一个空格，2、n个#即为n级标题，3、最多六个#）
## 二、atx风格标题可以以‘#'进行结束,只是为了美观，不限数量 #####
三、setext风格一级标题（在标题内容下一行为单纯的等号，有一个便足够）
=================
四、setext风格二级标题（在标题内容下一行为单纯的连字符，有一个便足够）
----------------


# [乙]练习使用引用块
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

# [丙]练习使用列表
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
* 引用01
  >引用02
  >>引用04
     >>>引用03每行的引用必须与列表的第一行缩进到同一位置才会被放进列表中。

