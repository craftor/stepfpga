软件安装(Lattice版)
=====================


下载
------

* Lattice版小脚丫使用的芯片是MachXO2系列，使用的开发工具是Dimaond。

	通常直接从
	`官方网站 <http://www.latticesemi.com/en/Products/DesignSoftwareAndIP/FPGAandLDS/LatticeDiamond.aspx>`_ 下载。
	但由于要账号，比较麻烦，这里直接给出下载链接：

	`Diamond 64bit <http://files.latticesemi.com/Diamond/3.8/3.8.0.115.3_Diamond_x64.zip>`_

	`Diamond 32bit <http://files.latticesemi.com/Diamond/3.8/3.8.0.115.3_Diamond.zip>`_

* Diamond软件会自动升级，所以如果版本老了，按软件提示升级即可。另外，想要使用Linux版的Diamond请读者自行去官方网站下载。

安装
------

按默认选项安装，一路Next即可。


License问题
-------------

由于Diamond软件需要License才能运行，读者可以到官方网站(www.latticesemi.com)申请免费License。
步骤可参照小脚丫外包装。


软件安装(Altera版)
======================


下载
------

* Altera [#f1]_ 版的小脚丫使用的是Max10系列的，使用的开发工具是Quartus Prime [#f2]_ 。Quartus Prime分三个版本，分别是：Pro、Standard和Lite，Max10使用Lite版本开发。

* 下载的内容应该包括三个：Quartus软件本身、Modelsim仿真工具、器件支持包。我们用的是Max10系列，只要保留Max10器件包即可，Cyclone系列的可以不下载。当然，如果硬盘够大，全部下载也可以。

* 由于下载需要账号登录，这里直接给出下载链接：

	`Quartus Lite 16.1 <http://download.altera.com/akdlm/software/acdsinst/16.1/196/ib_installers/
	QuartusLiteSetup-16.1.0.196-windows.exe>`_

	`Modelsim仿真工具 <http://download.altera.com/akdlm/software/acdsinst/16.1/196/ib_installers/ModelSimSetup-16.1.0.196-windows.exe>`_

	`Max10器件包 <http://download.altera.com/akdlm/software/acdsinst/16.1/196/ib_installers/max10-16.1.0.196.qdz>`_


安装 
------

按默认选项安装，一路Next即可。


License问题
-------------

Quartus Prime Lite 版不需要License


.. rubric:: 注：

.. [#f1] 2015年被Intel收购
.. [#f2] 以前叫Quartus II，现升级为Quartus Prime

