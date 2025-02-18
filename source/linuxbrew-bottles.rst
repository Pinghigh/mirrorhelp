============================
Linuxbrew Bottles 源使用帮助
============================

.. warning::
    由于上游原因，Linuxbrew 核心仓库（``linuxbrew-core``）自 2021 年 10 月 25 日（``brew`` 版本 3.3.0 起）被弃用，Linuxbrew 用户应迁移至 ``homebrew-core``。详见 :doc:`homebrew-core.git` 及 :doc:`homebrew-bottles`。

地址
====

https://mirrors.ustc.edu.cn/linuxbrew-bottles/

说明
====

Linuxbrew 预编译二进制软件包

收录仓库
========

* homebrew/linuxbrew-core

使用说明
========

请在运行 ``brew`` 前设置环境变量 ``HOMEBREW_BOTTLE_DOMAIN``，值为 ``https://mirrors.ustc.edu.cn/linuxbrew-bottles`` 。

临时替换：

::

    export HOMEBREW_BOTTLE_DOMAIN="https://mirrors.ustc.edu.cn/linuxbrew-bottles"

永久替换：

::

    # 对于 bash 用户
    echo 'export HOMEBREW_BOTTLE_DOMAIN="https://mirrors.ustc.edu.cn/linuxbrew-bottles"' >> ~/.bash_profile

    # 对于 zsh 用户
    echo 'export HOMEBREW_BOTTLE_DOMAIN="https://mirrors.ustc.edu.cn/linuxbrew-bottles"' >> ~/.zshrc

相关镜像
========
- :doc:`brew.git`
- :doc:`homebrew-bottles`
- :doc:`homebrew-core.git`
- :doc:`homebrew-cask.git`
- :doc:`homebrew-cask-versions.git`
- :doc:`linuxbrew-core.git`

相关链接
========

:官方主页: https://brew.sh/
:Bottles 介绍: https://docs.brew.sh/Bottles.html
