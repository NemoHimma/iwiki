工作流
==============

工作流概览
------------

.. note:: 
   未经审视的生活经不起推敲  ——苏格拉底

* 初衷：好记性不如烂笔头 
  #. 记录学习过程，将知识逐步内化

  #. 记录成长历程，一步步脚印，留下足迹

  #. 时常整理与反思，琐碎的思考与临时的日常规划用DayOne记录，技术思考与深刻感悟经过审视后用sphinx整理

* 目的：搭建一个多平台兼容【Mac| Linux | Win】的个人知识库

* 流程:
   #. 利用Github仓库存储代码与发布，在任意一台设备上都能写可分享的总结文档

   #. Win安装wsl2，使用Vscode在ubuntu24.04中远程开发 [1]_ 

   #. 配置git，通过ssh-key的方式关联github [2]_

   #. 通过Dotfiles仓库在wsl2中配置工作环境，必要时更换系统字体 [3]_

   #. 安装python3.10以上版本，利用venv创建虚拟环境，安装sphinx [4]_, 使用pydata-sphinx-theme主题 [5]_

   #. Windows安装Vscode， **reStructuredText** 语法写总结文档 [6]_


使用方式
--------------

.. rubric:: 参考资料
.. [1] `Windows最佳开发实践 <https://learn.microsoft.com/zh-cn/windows/wsl/setup/environment>`_
.. [2] `github-ssh-key配置 <https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent>`_
.. [3] `Dotfiles配置 <https://github.com/NemoHimma/Dotfiles>`_
.. [4] `sphix docs <https://www.sphinx-doc.org/en/master/usage/index.html>`_
.. [5] `pydata-sphinx-theme <https://pydata-sphinx-theme.readthedocs.io/en/stable/user_guide/layout.html>`_
.. [6] `reStructuredText <https://www.sphinx-doc.org/en/master/usage/restructuredtext/index.html>`_
