================
使用MP3文件学习
================

Aboboo 是开放式工具，能够使用MP3学习。

.. contents:: :local:

打开MP3文件
==============

在 **文件** 界面，点击主菜单的文件按钮：

.. image:: /images/main-menu-file.png

在弹出对话框中找到MP3文件，确认打开

.. image:: /images/open-mp3-file.png

.. Hint:: 
  1. 如果当前不在 **文件** 界面，主菜单的文件按钮后，不会弹出对话框，而是转到 **文件** 界面，这时，再次点击文件按钮弹出对话框。
  2. 批量添加MP3，请参看 :doc:`播放列表 </ref/playlist>` 。

加载MP3后，立即开始播放。

自动断句
===============
打开MP3后，软件会自动断句，完成音频采样，生成波形图，整个过程在后台执行，不影响正常播放，状态栏实时提醒进度。

采样生成学习所需的波形和断点，只在首次打开MP3时出现，一般可在几秒钟内完成。

.. image:: /images/status-bar-taking-sample.png

.. _mp3-lrc:

加载字幕
===========
Aboboo自动加载MP3文件所在目录下的同名LRC文件，LRC时间戳用作断点，文本用作音频的参照文本。

  * 也可以手动加载字幕，在主菜单的 **课件** 菜单中选择 **加载字幕**
  .. image:: /images/menu-load-subtitle.png

  * 在弹出对话框中打开LRC文件（或SRT文件）:
  .. image:: /images/load-lrc-or-srt.png
 
  * 加载字幕有可能改变断点、参照文本、译文等，用户决定怎样使用LRC :
  .. image:: /images/determine-how-to-use-lrc.png
  
  * 支持双语字幕，**自动分离到中文和英文** ：

    LRC字幕，能够自动分离内容到原文和译文::
    
      [00:00.88]Last week I went to the theatre.      上星期我去看戏。
      [00:05.36]I had a very good seat.      我的座位很好，
      [00:09.00]The play was very interesting.     戏很有意思，
      [00:13.00]I did not enjoy it.    但我却无法欣赏。
      [00:16.40]A young man and a young woman were sitting behind me.      一青年男子与一青年女子坐在我的身后，
      [00:21.92]They were talking loudly.    大声地说着话。
      [00:25.52]I got very angry.      我非常生气，
      [00:29.32]I could not hear the actors.    因为我听不见演员在说什么。
      [00:33.56]I turned round.     我回过头去
      [00:36.72]I looked at the man and the woman angrily.     怒视着那一男一女，
      [00:42.16]They did not pay any attention.    他们却毫不理会。
      [00:46.56]In the end,      最后，
      [00:48.04]I could not bear it.      我忍不住了，
      [00:51.88]I turned round again.     又一次回过头去，
      [00:55.36]'I can't hear a word!'    "我一个字也听不见了！"
      [00:58.76]I said angrily.     我生气地说。
      [01:02.32]'It's none of your business,'      "不关你的事，"
      [01:05.16]the young man said rudely.      那男的毫不客气地说。
      [01:08.88]'This is a private conversation!'     “这是私人谈话。”

    SRT字幕，也能够自动分离内容到原文和译文::
    
      1
      00:00:00,880 --> 00:00:03,960
      Last week I went to the theatre.    上星期我去看戏。
      
      2
      00:00:05,360 --> 00:00:07,680
      I had a very good seat.    我的座位很好，
      
      3
      00:00:09,000 --> 00:00:11,480
      The play was very interesting.      戏很有意思，
      
      4
      00:00:13,000 --> 00:00:14,960
      I did not enjoy it.     但我却无法欣赏。
      
      5
      00:00:16,400 --> 00:00:20,480
      A young man and a young woman were sitting behind me.    一青年男子与一青年女子坐在我的身后，
      
      6
      00:00:21,920 --> 00:00:24,120
      They were talking loudly.     大声地说着话。
      
      7
      00:00:25,520 --> 00:00:27,840
      I got very angry.    我非常生气，
      
      8
      00:00:29,320 --> 00:00:32,080
      I could not hear the actors.     因为我听不见演员在说什么。
      
      9
      00:00:33,560 --> 00:00:35,160
      I turned round.      我回过头去
      
      10
      00:00:36,720 --> 00:00:40,320
      I looked at the man and the woman angrily.      怒视着那一男一女，
      
      11
      00:00:42,160 --> 00:00:44,920
      They did not pay any attention.     他们却毫不理会。
      
      12
      00:00:46,560 --> 00:00:47,800
      In the end,    最后，
      
      13
      00:00:48,040 --> 00:00:50,360
      I could not bear it.    我忍不住了，
      
      14
      00:00:51,880 --> 00:00:53,720
      I turned round again.      又一次回过头去，
      
      15
      00:00:55,360 --> 00:00:58,360
      'I can't hear a word!'     "我一个字也听不见了！"
      
      16
      00:00:58,760 --> 00:01:00,720
      I said angrily.      我生气地说。
      
      17
      00:01:02,320 --> 00:01:04,720
      'It's none of your business,'    "不关你的事，"
      
      18
      00:01:05,160 --> 00:01:07,440
      the young man said rudely.    那男的毫不客气地说。
      
      19
      00:01:08,880 --> 00:01:14,040
      'This is a private conversation!'      “这是私人谈话。”
      
.. Hint:: 
  缺少参照文本时，一些功能不可用或不完整，如不能造句练习，听写时无法校对。


断点批量移动
============
有时遇到时间轴整体提前或落后的字幕，相对时间点正确，但起点不正确，这样的字幕，需要重新校准第一句的时间轴，其它句子随动。

.. image:: /images/P1054.PNG


.. _mp3-checking-text:

制作听写校对文本
================
* **第一步** 打开MP3，进入 **学习** >> **单句听写** >> **导入** >> **打开文件到单句听写** 。

  .. image:: /images/P1032.PNG

|

* 确认操作：

  .. image:: /images/P1033.PNG
    :width: 400px

|

* **第二步** **导出** >> **保存为该音频的参照文本** 。

  .. image:: /images/P1034.PNG

|

* 确认操作：

  .. image:: /images/P1035.PNG
    :width: 350px

|

* **第三步** **操作** >> **清除本次听写** 。

  .. image:: /images/P1036.PNG

|

* 确认操作：

  .. image:: /images/P1037.PNG
    :width: 400px

|

* 听写可以校对了！

  .. image:: /images/P1038.PNG
    :width: 500px

