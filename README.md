# Overview

Fascam软件组成中，算法功能是通过matlab simulink实现.

Fascam Target通过C-Sfunction的方式提供接口，在simulink中实现BSW相关API的调用。

# 接口定义

算法和软件之间的接口主要有三类**：**

* Vehicle:_**fascam\_matrix.dbc**_

摄像头模块和车辆其他节点通信矩阵。

* Eyeq signals:** me**_**dbcs**, **Hirain\_ME-EYEQ\_COM.xls**_

EYEQ SPI应用层协议，以及补充说明。

* System signals:_**FASCamSysInterfaceOfSwVxx.dbc**_

系统默认功能配置，系统需要存储的一些信息等。

# 安装

System Requirement

| OS | windows 32/64 |
| :--- | :--- |
| matlab | matlab2011b/matlab2016b |

Install

In matlab command window:

```
run install.m
```

Unistall

In matlab command window:

```
run uninstall.m
```

# [模块说明](/chapter1.md)



