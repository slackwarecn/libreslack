# libreslack
Deblob Slackware   
## 自由化你的Slackware
——去掉非自由软件   

**blob.list**  
- 包含了自 Slackware.com 官方repo里安装的**未以自由开源软件许可证发布**的软件。
- 也包含了 Linux内核，因为其内也有非自由的固件；请使用完全自由的 linux-libre(https://www.fsfla.org/ikiwiki/selibre/linux-libre/)
- 还有 Mozilla 家族，其许可证中商标的使用并不自由。
- 参考自：[Freenix](http://freenix.net/fxp/freeslack64-14.2/source/fxp/cfg/) 

## Usage
oneliner：  

  `while read line; do removepkg $line; done < blob.list`  

最后更新：2018.09.25
