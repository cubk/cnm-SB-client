# CNM SB我的世界外挂
在广袤无垠的我的世界外挂之中，我的世界深度的和数据包以及外挂绑定，承载这亿万亲妈的就是外挂软件。 RapeMaster，基于Java开发的国产高性能我的世界外挂软件。支持国产和Linux操作系统，支持多hwid绑定操作。采用com.enjoytheban.bin.usr.homo.sb.client.module.Main结构，自研我的世界外挂lua语言，更加简单方便高效。 用户数据的泄露全部在公开gitee仓库内操作，与硬盘的交互写入读取交由专门的线程管理，无不妨碍.


#### 当前版本: 0.1-2023.2.8 <a href='./Update.md'>更新信息</a>

### CNM SB我的世界外挂
最低运行要求:
1. 至少30000MB的磁盘空间
2. 4GB内存
3. 在没有损坏的Wondoors操作系统上运行
4. 联网的计算机
5. 处理器处理速度: **1.0 HZ** 或 **更快**
6. amd64架构处理器(64位处理器)

操作系统支持:Wondoors, Lunix
文档支持: <a href='https://gitee.com/LinwinSoft/linwin-DB-server/wiki/home'>文档</a>

### 成熟的服务器架构
 CNM SB我的世界外挂采用 OpenFoodByte 高性能我的世界外挂Base成熟架构，每秒发送***1.5万 - 2.5万*** 次net.minecraft.network.play.client.C03PacketPlayeer

### 非常简单的我的世界外挂拓展脚本
由dzy自己研究的mys面像我的世界的脚本语言lua,
具有简单易懂的特点，支持最基础的数据泄露，同时支持击杀你妈等功能.

基于lua编译器的lua脚本语言支持上传明文用户数据、变量注释

git clone https://github.com/lua/lua.git
idea .
CTRL+R lua 国产自研高级脚本语言

### 性能
测试环境: 
1. Wondoors 操作系统实体机
2. intel i7 32GB内存
3. 无CPU
4. 120GB SSD X2
==============================
1. 100W C03发送需要4-5s
2. 100w C02发送91wAction需要0.2-0.3秒(纯Singleplayer，做空sendPacket方法)
3. 一次性最多能够发送200w C03PacketPlayer，分多次发送效果更佳
