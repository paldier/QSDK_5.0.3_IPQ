#QSDK_5.0.3_IPQ

简介
=======================
高通的QSDK IPQ40xx平台5.0.3版本，包含qca-wifi驱动。此代码来自PandoraBox开发团队的固件下载服务器，  
可以公开下载的，本仓库只是整理了一下。  

[dl目录下载地址](https://downloads.pangubox.com/sources/)  
[源码下载地址](https://downloads.pangubox.com/lintel/qsdk-5.0.3.zip)  
[恩山大佬lintel](https://www.right.com.cn/forum/space-uid-37585.html)  

编译
=======================
./scripts/feeds update -a  
./scripts/feeds install -a -f  
cp qca/configs/ipq.config .config  
make defconfig  
make V=s  


免责声明
=======================
1.本仓库源码是从[PandoraBox](https://downloads.pangubox.com/lintel/qsdk-5.0.3.zip)开放，  
PandoraBox团队应当在明确没有违反高通NDA的前提之下，向大众开放QSDK源代码，本人只是整理代码了，  
所以应当由PandoraBox团队承担有关法律责任，于本人无关。
2.本仓库源码未经验证，不确定是否有BUG，或者存在有后门，请自行测试，本人不对此问题任何负责。  
3.本仓库源码仅供学习和研究使用，不得禁止非法传播和用于任何商业用途。  
4.本仓库源码著作权为PandoraBox团队。如有侵犯著作权或其他合法权利的，请联系我。  
