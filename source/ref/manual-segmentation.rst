========
手工断句
========

.. rubric:: 智能断句后，如果个别断点不理想，可以手工微调，在主界面波形面板操作，既能用键盘，也能用鼠标，主波形为主，次波形辅助。

.. contents:: :local:

.. figure:: /images/main-wave-and-sub-wave.png
  :align: center

  主波形为主 / 次波形辅助

在主波面板上使用鼠标断句
================================
在主波形上断句时，波形面板动态提醒您正在进行的操作:

* 插入断点：找到要插入的位置，按住 :kbd:`Ctrl`，单击左键，在点击位置添加新断点，句子一分为二。

  .. figure:: /images/manual-segmentation-insertion.png
    :align: center

    ⌨ Ctrl + 🖱 左键 ⇨ 插入断点

|

* 删除整句：找到要删除的句子，按住 :kbd:`Ctrl-Alt`，单击右键，该句的整句标记被删除。

  .. figure:: /images/manual-segmentation-deletion.png
    :align: center

    ⌨ Ctrl + Alt + 🖱 右键 ⇨ 删除整句

|

* 调整起点：找到要调整的句子，鼠标移动悬停在左边线底部时，句子边线被高亮，此时按住左键，左右滑动以调整句子起点，松开后新起点生效。
  
  .. figure:: /images/manual-segmentation-moving-start-point.png
    :align: center

    按住 🖱 左键 滑动 ⇨ 调整起点

|

* 调整终点：操作与调整起点类似，不同的是鼠标悬停在右边线底部，调整句子的终点。
  
  .. figure:: /images/manual-segmentation-moving-end-point.png
    :align: center

    按住 🖱 左键 滑动 ⇨ 调整终点

|
  
* 合并上句：找到句子的起始断点，按住 :kbd:`Ctrl`，单击右键，与上句合并；
  
  .. figure:: /images/manual-segmentation-merging-with-previous.png
    :align: center

    ⌨ Ctrl + 🖱 右键 ⇨ 合并上句

|
    
* 合并下句：找到句子的结束断点，按住 :kbd:`Ctrl`，单击右键，与下句合并。
  
  .. figure:: /images/manual-segmentation-merging-with-next.png
    :align: center

    ⌨ Ctrl + 🖱 右键 ⇨ 合并下句

|
    
.. important:: 合并断点后，相关的参照文本、译文、读音标记、单句听写等内容也自动合并，两句间的文本以空格分隔。
  
在次波面板上使用鼠标断句
================================
如果起点或终点位置不够精确需要微调，主波形太短不便调整，可用次波微调：

* 插入断点：按住 :kbd:`Ctrl-Alt`，单击左键，在点击位置添加新断点。

  .. figure:: /images/manual-segmentation-sub-wave-insertion.png
    :align: center

    ⌨ Ctrl + Alt + 🖱 左键 ⇨ 插入断点

|

* 微调起点：按住 :kbd:`Ctrl`，单击左键，调整起点。
  
  .. figure:: /images/manual-segmentation-sub-wave-moving-start-point.png
    :align: center

    ⌨ Ctrl + 🖱 左键 ⇨ 微调起点

|

  
* 微调终点：按住 :kbd:`Ctrl`，单击右键，调整终点。

  .. figure:: /images/manual-segmentation-sub-wave-moving-end-point.png
    :align: center

    ⌨ Ctrl + 🖱 右键 ⇨ 微调终点

|

使用键盘快速断句
================

键盘只能插入和合并断点，一边听一边断句，听完一句，马上按下 ⌨ :kbd:`F5` 插入一个断点。

* ⌨ :kbd:`F5` 插入断点：当前播放位置插入新断点，句子一分为二。
* ⌨ :kbd:`F10` 合并上句：当前句合并到上一句。
* ⌨ :kbd:`F11` 合并下句：当前句合并到下一句。

以上是默认热键，您可以在参数设置中重新定义它们。

