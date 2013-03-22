打印预览时“成绩单”右侧内容超出A4纸张
########################################################

一般来说，成绩单能自适应纸张宽度，随着纸张宽度的变化，成绩单自动伸展或折行。

成绩单标题长度不确定，能够自动折行，但当标题是连续的西文字符，缺少空格和连字符，有可能迫使成绩单超宽排版，软件默认使用A4纸张幅面预览，超过右侧边界的内容无法正常显示。

* 超长标题引起超宽排版:

  .. image:: /images/troubleshooting/print-preview-title-over-edge.png

* 文件名有空格和连字符能正常折行:

  .. image:: /images/troubleshooting/print-preview-title-word-break.png


成绩单标题由课件名和文件名组合而成，规范的课件命名能避免此问题，由于超宽而显示不完整的情况不常见，如果你恰好遇到，以下三个办法可以解决:

1. **改变纸张**: :menuselection:`预览 --> 打印 --> 打印机 --> 属性 --> 布局 --> 方向 --> 横向` ，成绩单自适应纸张宽度，足够宽的纸张（如A4横向）能完整打印成绩单。

  .. image:: /images/troubleshooting/print-preview-change-layout.png
     
2. **导出图片**: 使用成绩单的“存为图片”功能，可以摆脱纸张宽度限制，完整输出成绩单。

  .. image:: /images/troubleshooting/report-card-save-as-image.png

3. **改文件名**: 听写前，改短文件名或在文件中加入空格，这样一来，再长的内容也可以自动折行。

  * 把“下划线”改成“空格”::
 
      修改前: TPO24_Writing_IntegrateWriting_Listening.q99
      修改后: TPO24 Writing IntegrateWriting Listening.q99
   
  * 也可以改短文件名::
   
      修改前: TPO24_Writing_IntegrateWriting_Listening.q99
      修改后: TPO24.q99
   
