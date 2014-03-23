======
查字典
======

.. rubric:: 字典不能用，请首先 :ref:`检查字典完整性 <check-dictionary-data-files>` 。

.. contents:: :local:

进入字典
========
有三种途径进入字典: 

* :menuselection:`主菜单 --> 字典` （热键 :kbd:`F12`）

* 在单词上 :menuselection:`右键弹出菜单 --> 英英字典中查询` （ :kbd:`Ctrl-鼠标右键`）

  .. image:: /images/dictionary-context-menu.png
  
* 在单词上 :menuselection:`右键弹出菜单 --> 迷你字典中查询` （ :kbd:`Ctrl-鼠标左键`）
  
  .. image:: /images/dictionary-mini.png
  
支持六种查询方式
=================
1. 完全: 与查询字符串完全一致；
2. 前向: 以查询字符串开头；
3. 后向: 以查询字符串结尾；
4. 包含: 包含查询字符串；
5. 关键语素: 包含查询字符串，字符可以不连续，输入 **abvtion** 查到 **abbreviation** 。
6. 正则表达式: 供了解正则表达式的用户使用。

查询选项
========
* 包含相关单词: 选中该选项，查询结果包括近义词、反义词等相关词，
  查询 **sweet** ，结果中包含同义词 **dessert**。
* 包括单词时态及变形: 选中该选项，查询结果包括时态和变形；
* 查询后立即朗读: 查到单词后自动朗读。

英英字典
=============
* edd.dat(5.2 MB) 五万分级单词，也是其他字典的基础
  
  .. image:: /images/dictionary-overview-edd.png

* 波形面板
  
  .. image:: /images/dictionary-wave-panel.png

* 可随时进入随意读，跟读单词。
  
  .. image:: /images/dictionary-word-spoken-at-will.png

单词图片字典
=============
cwp.dat(58 MB) 五千单词的优质图片

.. image:: /images/dictionary-overview-cwp.png

* 点击小喇叭朗读，单击小加号加入生词本
* :kbd:`Ctrl-右键` （或双击左键）查询单词
* :kbd:`Ctrl-左键` 迷你字典查询单词
  
英汉/汉英字典
=============
ced.dat(32 MB) 三十万英汉/汉英详尽解释

.. image:: /images/dictionary-overview-ced.png

常用搭配字典
=============
dpd.dat(3.4 MB) 两万单词搭配用法

.. image:: /images/dictionary-overview-dpd.png

例句字典
=============
sdp.dat(929 MB) 十五万真人语音例句

* 点击小喇叭朗读例句，单击小加号加入句库。

  .. image:: /images/dictionary-overview-sdp.png

* 可以随时进入随意读，跟读例句。

  .. image:: /images/dictionary-example-spoken-at-will.png

* 例句字典可以导出成MP3和LRC文件，方便您在mp3播放器上学习。

  :menuselection:`例句 --> 例句导出成MP3`

  .. image:: /images/dictionary-example-export.png

单词读音
====================
* mall.dat(108 MB) 真人美音
* ball.dat(151 MB) 真人英音

  :menuselection:`菜单 --> 参数设置 --> 单词发音 --> Aboboo自带语音库 --> 语音库优先选择`

  .. image:: /images/dictionary-choose-mall-or-ball.png