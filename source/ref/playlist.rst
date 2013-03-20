================
播放列表
================

.. rubric:: 播放列表不干扰学习，进入学习模式后列表自动隐藏，点击主导航菜单的“文件”找回播放列表。

.. contents:: :local:

列表内容
==============

* Aboboo课件文件：专指 **.Q99** 文件。
* 普通媒体文件：所有Aboboo能播放的音频和视频，请参考 :ref:`Aboboo支持的音视频文件格式 <file-format-supported>` 。
* 最近打开的文件: 保留最近打开的文件历史，方便您快速继续上一次的学习。

.. image:: /images/playlist-overview.png

.. tip:: 
   * 最近打开的文件数可以设置 :menuselection:`文件 --> 参数设置 --> 操作习惯 --> 历史记录 --> 最近打开的文件数` 。
   * 支持 :kbd:`方向键`、:kbd:`PageDown`、:kbd:`PageUp`、:kbd:`Home`、:kbd:`End`、:kbd:`Delete`。


添加
=========

* 用菜单添加: 向列表中添加文件或文件夹
* 拖放式添加: 用鼠标将文件从“我的电脑”或“资源管理器”拖放到播放列表，单文件、多文件和文件夹均可拖放。
* 关联课件自动添加: 如果勾选了 :menuselection:`文件 --> 参数设置 --> 基本设置 --> 关联Q99课件文件` ，则以后双击打开课件时，自动添加文件到播放列表。

.. image:: /images/playlist-menu-add.png


移除
====
在播放列表上按 :kbd:`Delele` 删除，也可以 :menuselection:`弹出菜单 --> 从播放列表中清除文件` 

.. image:: /images/playlist-menu-remove.png

批量操作，清空某结点或清空列表:

.. image:: /images/playlist-menu-clear.png

.. tip:: 删除节点下所有文件的信息可以批量恢复课件内容 请参考 :ref:`如何恢复课件内容 <discard-courseware-local-data>`


排序
====
可使用鼠标拖放文件来改变文件在同级列表中的次序，也可以设置排序规则。

.. image:: /images/playlist-menu-sorting.png

去重
====
一个文件在列表中允许出现多次，也可以“去重”。

“文件全路径名”相同才算重复。内容相同，名称不同，不算重复；名称相同，目录不同，也不算重复。

.. image:: /images/playlist-menu-remove-duplicate.png


显示方式
==================
设置文件显示方式，课件文件可选 **显示到一级分类** 或 **显示到二级分类** ，普通媒体可按最后一级目录名分类显示或按完整目录名分类。

.. image:: /images/playlist-menu-show-directory-structure.png

播放模式
======================

默认为“单首播放”，还可以选择“单首循环”、“顺序播放”、“循环播放”、“随机播放”。

.. image:: /images/playlist-menu-play-mode.png

保存和加载m3u
=======================

保存列表内容到播放列表文件(.m3u):

.. image:: /images/playlist-menu-save-m3u.png

加载已保存的播放列表文件(.m3u):

.. image:: /images/playlist-open-m3u.png

自动同步磁盘目录到播放列表
==================================================
“文件目录动态监控功能”默认关闭，通过 :menuselection:`文件 --> 参数设置 --> 操作习惯 --> 文件目录动态监控` 打开后，指定目录的文件变化将被实时同步到播放列表。 

.. image:: /images/preference-sync-directory-to-playlist.png

