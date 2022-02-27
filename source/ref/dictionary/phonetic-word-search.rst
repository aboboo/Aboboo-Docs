========
听音查字
========

.. contents:: :local:

进入听音查字
============
听音查字是字典的子功能，必须先进入字典，然后点击 **切换按钮** 或按下 ⌨ :kbd:`Ctrl-D` 切换到听音查字：

  .. figure:: /images/phonetic-word-search-switch.gif
    :align: center

    快速切换单词查询/听音查字

进入听音查字后，界面局部变化：

  .. figure:: /images/phonetic-word-search.png
    :align: center

    听音查字的功能面板

再次切换可以回到单词查询。

录入音标查询单词
================
不要求全部录入，只需按顺序录入部分关键音标，录入越多，匹配越准确。

例如单词 **abbreviation** 的拼写记不全，但能肯定音标里依次有 **b** **r** **v** **n** 等关键音标，录入 **brvn** ，可查到 **abbreviation** 。

怎样录入音标字符
================
输入框的下方有一个快捷面板：
  

  .. figure:: /images/phonetic-select-panel.png
    :align: center

    音标字符快捷输入

  鼠标点击按钮输入音标字符，面板上找不到的音标符号，都能与键盘一一对应，用键盘直接录入。

  面板上的音标字符也都可以通过键盘录入，图标左侧大写字母和数字是键值，图标右侧是其对应的音标符号，要录入某个音标，录入其对应的键值即可。

特殊的斜线符“/”
=========================

* 录入 **lus** ,可以查询到loose、loosen、exclusive等单词；
* 录入 **/lus** ,只能查询到以l开头发音的单词，所以可以查询到loose、loosen 等单词，但查询不到exclusive；
* 录入 **lus/** ,只能查询到以s结尾发音的单词，所以可以查询到loose、但查询不到loosen，exclusive；
* 录入 **/lus/** ,只能查询到以l开头发音，并且以s为结尾发音的单词，所以可以查询到loose、luminous等单词，
  但查询不到loosen、exclusive等单词。
  
.. tip:: 斜线符 **/** 只能出现在整个的音标开头或结尾。

选择过滤范围
============

  过滤范围显著影响查询结果，录入 **/frd/** ：

  * 1000以内：没有匹配
  * 3000以内：只有1个(friend)
  * 5000以内：还是1个
  * 10000以内：4个
  * 30000以内：17个
  * 全部(不过滤)：200个

  30000以内的查询结果：
  
  .. figure:: /images/phonetic-word-search-select-range.png
    :align: center

    选择过滤范围

  .. tip:: 
    请选择恰当的过滤范围，范围太小查不到，范围太大干扰多。
