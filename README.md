# Fascam Target

Fascam软件组成中，算法功能是通过matlab实现。

# ![](/assets/software_arch.png)接口定义

算法和软件之间的接口主要有三类**：**

* Vehicle:fascam\_matrix.dbc

摄像头模块和车辆其他节点通信矩阵。

* Eyeq signals: me_dbcs, Hirain\_ME_-EYEQ\_COM.xls\_

EYEQ SPI应用层协议，以及补充说明。

* System signals:FASCamSysInterfaceOfSwVxx.dbc

系统默认功能配置，系统需要存储的一些信息等。

# 实现方式

Fascam Target通过C-Sfunction的方式提供接口，在simulink中实现相关API的调用。

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



