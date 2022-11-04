###解决Ubuntu22.04下安装WPS提示字体缺失
1. 执行如下命令：

   将缺失的字体下载到本地git clone git@github.com:SJMya/WPS_FontsForUbuntu22.04.git

   ```
   git clone git@github.com:SJMya/WPS_FontsForUbuntu22.04.git
   ```

2. 将字体移动到`/usr/share/fonts/`下

   ```
   #在下载的字体文件夹目录中
   cp * /usr/share/fonts/
   ```

3. 关闭WPS，重新打开即可。



