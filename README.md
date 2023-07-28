# Overview
The product：D-Link DIR-600
Latest version(July 28, 2023)：2.18 B5
Affected version：2.18 B5 <= 
Manufacturer's website information：[https://www.dlink.com/](https://www.dlink.com/)
Firmware download address：[https://www.dlinktw.com.tw/techsupport/ProductInfo.aspx?m=DIR-600](https://www.dlinktw.com.tw/techsupport/ProductInfo.aspx?m=DIR-600)
# Details 
In soap.cgi, since the parameters of the request message are not checked for security, the command is directly concatenated and passed into the system function, so that the attacker can implement command injection by constructing message parameters.
![image.png](https://cdn.nlark.com/yuque/0/2023/png/22319187/1690508241204-79e02fe6-6c6a-42a8-89d3-39eb8763a4f6.png#averageHue=%23fefefe&clientId=ued26898e-9d8e-4&from=paste&height=343&id=u0b8938f4&originHeight=343&originWidth=762&originalType=binary&ratio=1&rotation=0&showTitle=false&size=27171&status=done&style=none&taskId=u13a3d56e-bedf-4cbe-bb9f-1c5875251e1&title=&width=762)

# POC Video
The POC video is in the attach
