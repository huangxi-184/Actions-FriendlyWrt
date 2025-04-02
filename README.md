# 使用 GitHub Actions 编译 FriendlyWrt
### 基本信息 
- 用户名：root
- 密码：password
- 后台IP：192.168.2.1
- 固件下载地址： https://github.com/friendlyarm/Actions-FriendlyWrt/releases
- 更多使用说明: https://wiki.friendlyelec.com/wiki/index.php/Template:FriendlyWrt21/zh
### 固件说明
- 同一固件文件同时支持安装至SD和eMMC，不作区分
### 如何将固件写入eMMC  
- 先将固件写入一张SD卡，然后从SD启动系统，访问FriendyWrt后台页面，进入菜单“系统”->“eMMC刷机助手”，上传固件文件直接刷入即可，文件无需解压，写入完成后，将SD卡弹出, 设备会自动重启并从eMMC引导系统。