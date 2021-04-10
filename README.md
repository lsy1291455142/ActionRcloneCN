# 科学ADV资源站专用同步Action1
使用[蜜桃猫](https://peachcat.org/archives/996)前辈制作的世纪互联版rclone进行文件迁移,我个人完成了Secret保存配置文件的处理。
# 使用
首先Star并Fork本仓库。

用这个[别人上传好的修改版本](https://github.com/zhenglix/rclone--)在你的设备上进行Token获取等操作。

完成配置后在Repo设置里创建名为CONF的Secret,将你的rclone.conf文件内容一股脑地扔进去。

修改.github/workflows/sync.yml文件,将ODGD之类的盘符修改为你的盘符。

推送来启动Action。

每6小时自动启动一次,如因为滥用被Github封号,本人不承担任何责任。
# 其他
我个人在搞的项目,欢迎顺手Star

[科学ADV图书馆](https://sciadv.mcseekeri.top)

[源代码Repo](https://github.com/MCSeekeri/sciadv)
