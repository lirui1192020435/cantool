cantool装置的需求：
（1）需要接受CAN总线所传输过来的数据，而这里的CAN总线其实是虚拟不存在的。

（2）经过cantool装置将所接受的数据转化为所需要的格式。

（3）将转化后的文本传送到所开发的软件中。

而这次我主要负责的就是做数据接受和转换，以上仅为我个人对cantool装置的理解。欢迎其他组员多提意见。
何静
#CanTool项目需求分析：
1、CanTool装置与上位机通过USB串口或蓝牙RFComm实现UART串口通信。

2、上位机与CanTool装置之间的信息传送方式使用ASCII码格式+ \r（即0x0d）方式进行信息交换。

3、CanTool装置接收CanToolApp发送的CAN信息并显示并发送到CAN总线。

4.进行单元测试－功能测试－集成测试－场景测试－系统测试－Alpha/Beta Test。

5.以Arduino微控制器为基础设计CanTool硬件装置，实现CanTool装置信号的发送和接收。
