韩语课件显示不正常
############################

韩语课件中的字符显示出来是一些方格子：

.. image:: /images/troubleshooting/asian-characters-appear-only-as-squares.png

该问题没有明确的解决方法，只能尝试：

1. 如果只有Aboboo不能显示韩语，其他软件如“资源管理器”能显示，可能只是字体设置不恰当，请在界面中选择使用Unicode字体，如“微软雅黑”等。

2. 如果所有软件均不能显示韩语，请确认您的windows已安装韩语语言包，具体办法请用谷歌自助。 

3. 如果能找到的各种办法都未奏效，再试个偏方。

Here is the solution:: 

   1) Make sure you log out of the active user who has the problem. I tried by simply closing all the programs and going to the admin account but the problem was not solved. I really had to log out with the current user.

   2) Log in as the admin user of the computer.
   
   3) Delete everything in: C:\\Users\\user-with-the-problem\\AppData\\Local\\Microsoft\\Internet Explorer
      (change "user-with-the-problem" with the username of the user having the problem, ie the user you use when you have the problem)
   
   4) Log back on the user you were using and launch Skype. The problem should be solved.
   
   原文摘录自Skype论坛，未经翻译，如果有效，请到论坛反馈“它真的有用”。


问题解决后，界面显示韩语:

.. image:: /images/troubleshooting/display-asian-characters-correctly.png

