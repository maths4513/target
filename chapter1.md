# Fascam Simulink Target

![](/assets/simulink_target.png)

* [**vtp\_function**](/vtpfunction.md)

提供CAN 网络信号访问接口，读信号以及写信号等操作，Based on CANStack-VTP by Mentor.

* [**Com\_function**](/comfunction.md)

提供CAN网络信号访问接口，读信号以及写信号等操作， Based on GenoStack-COM by Hirain.

* **checksum\_function**

提供checksum  接口，仅支持SAIC XOR和SAIC SAEJ1850。

* [**eyeq\_function**](/eyeqfunction.md)

提供EYEQ信好访问接口，读信号以及写信号等操作，Based on MESPI Stack byHirain.

* **il\_function**

提供CAN网络信号访问接口，读信号以及写信号灯操作，Based on CANbeded-IL by Vector.

* **general**

提供System访问接口，读变量以及写变量.

* **msgpack**

针对CANStack-VTP, 仅提供了针对信号的API,并未提供针对报文的访问接口，而chekcsum等计算需要针对报文按字节进行运算，msgpack提供通过信号来进行message的组包，通常和checksum\_funcion一起使用。

