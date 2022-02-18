================
MP3听写
================

Aboboo 是开放式工具，能够使用MP3学习。

.. contents:: :local:

打开MP3文件
==============

在 **文件** 界面，点击播放列表顶部工具条的打开按钮：

.. figure:: /images/main-menu-file.png
  :align: center

  打开文件

在弹出对话框中找到MP3文件，确认打开。

.. figure:: /images/open-mp3-file.png
  :align: center

  选择文件

.. Hint:: 
  批量添加MP3，请参看 :doc:`播放列表 </ref/playlist>` 。


自动断句
===============
首次打开MP3，软件自动完成该MP3的音频采样，生成波形图和断点数据，整个过程在后台执行，不影响正常播放，状态栏实时提醒进度。

采样生成学习所需的波形和断点，只在首次打开MP3时出现，一般可在几秒钟内完成。

.. figure:: /images/status-bar-taking-sample.png
  :align: center

  状态栏实时提醒采样进度

.. figure:: /images/message-box-sample-taken.png
  :align: center

  完成智能断句后的提示

.. _mp3-lrc:

加载字幕
===========
Aboboo自动加载MP3文件所在目录下的同名LRC文件，LRC时间戳用作断点，文本用作音频的参照文本。

  * 同名字幕文件自动加载:

  .. figure:: /images/lrc-auto-loading.png
    :align: center
    
    自动加载该目录下的文件名相同的字幕文件

  * 也可以手动加载字幕: :menuselection:`操作 --> 字幕 --> 加载字幕`

  .. figure:: /images/menu-load-subtitle.png
    :align: center

    手动加载字幕

  * 在弹出对话框中打开LRC文件（或SRT文件）:

  .. figure:: /images/load-lrc-or-srt.png
     :align: center

     打开字幕文件

  * 加载字幕有可能改变断点、参照文本、译文等，用户决定怎样使用LRC:

  .. figure:: /images/determine-how-to-use-lrc.png
     :align: center

     使用LRC断句
 
  * 加载双语字幕时，勾选对话框中的 **自动分离内容到原文和译文** ，能够将字幕内容分别加载到原文和译文:

  .. figure:: /images/check-auto-split-text-and-tran.png
    :align: center

    自动分离原文和译文

  * 双语字幕示例: 
    
    LRC字幕示例，这样的内容能够被自动分离到原文和译文::
    
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

    SRT字幕示例，这样的内容也能够被自动分离到原文和译文::
    
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
      

.. _dictation-checking-and-correcting:

听写和校对
================

* Aboboo有三种难度递进的听写功能，“抠词”、“单句”、“自由”，分别对应“单词”、“句子”、“篇章”。
  
  “抠词听写”必须有“参照文本”。
  
  “单句听写”和“自由听写”可以没有参照文本，但如果需要校对，就必须有“校对文本”。
    
.. figure:: /images/menu-dictation.png
  :align: center

  抠词听写 → 单句听写 → 自由听写


* 单句听写和自由听写时，如果缺少“校对文本”，软件会提示您“加载校对文本”:  

.. figure:: /images/status-bar-checking-text-nonexistence.png
  :align: center

  校对必须有“校对文本”  

* 进入“校对文本编辑界面”，完成导入和编辑后，返回听写，校对器自动加载新的校对文本并重新校对:

.. figure:: /images/load-checking-text.png
  :align: center

  导入和编辑校对文本

* 实时校对:

.. figure:: /images/sent-dictation-checking-on-the-fly.png
  :align: center

  实时校对提醒
  
* 按下 :kbd:`F1` 进入校对提示:

.. figure:: /images/sent-dictation-checking-window.png
  :align: center

  :kbd:`F1` 校对提示

校对文本自动加载规则
================================

1. 如果当前文件有参照文本，则采用参照文本作为校对文本；
2. 如果没有参照文本，而且是加载了以前听写记录继续听写的，则采用所加载听写记录的校对文本；
3. 您也可以通过“校对文本编辑界面”从其他文件中加载校对文本，或者直接编辑校对文本。

消除标点符号对正确率的影响
=============================

有些课件资料的参照文本的含有非标准的标点符号，英文单引号 :kbd:`'` 很多误作全角字符 :kbd:`’` ，

即使听写结果没问题，成绩单显示标点有错，遇到这种情况，可以把这些特殊的符号加入到 :menuselection:`参数设置 --> 基本设置 --> 听写设置 --> 校对标点忽略列表`:

.. figure:: /images/preference-basic-checking-ignore-list.png
  :align: center

  听写设置

* 默认列表: :kbd:`‘='|’='|`='|。=.|“="|”="|…=...|` ，向列表添加的内容须遵守列表规则。
* 列表规则: :kbd:`=` 左右两边的字符等价，:kbd:`|` 分割多组等价字符。
* 强制校对：:kbd:`,;.:?!"+=-&%$#` ，可强制校对的标点符号。

.. tip:: 也可以在课间播放界面使用 :menuselection:`操作 --> 编辑句子` 直接修改参照文本。

