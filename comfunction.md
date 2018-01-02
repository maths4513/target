* **com\_**_**signal\_read**_

![](/assets/com_signal_read.PNG)

**input**: none  
**output**: raw signal value  
**parameters**:

| Name | Datatype | Description |
| :--- | :--- | :--- |
| ComSignalName | String | signal name defined in geno |
| ComHandleApi | String | Geno com signal read api name |
| SignalType | Enum | data type defined in dbc |
|  |  |  |

* **com\_signal\_write**

![](/assets/com_signal_write.PNG)

**input**: raw signal value  
**output**: none  
**parameters**:

| Name | Datatype | Description |
| :--- | :--- | :--- |
| VtpSignalHandleName | String | signal handle defined in v\_hand.h |
| VtpSignalType | DataType |  |
| VtpSignalTypeNCF | none | obsolete |
| StartBit | none | obsolete |



