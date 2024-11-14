小白/新手/打不开/不知道下哪一个文件,请看如下说明.

如果你的 电脑(MacBook) 芯片是 苹果芯片(Apple silicon)

那就下载 mac-arm64.dmg 结尾的文件(第4行),否则下载 mac-x64.dmg 结尾的文件(第7行)

下载后打开zip压缩包,再打开dmg文件,再将应用移动到Applications

打开终端(启动台里面找),输入下面👇命令

xattr -dr com.apple.quarantine /Applications/FreeTube.app

然后回车,再打开FreeTube应用即可.

还是不行?

打开 系统设置 -> 隐私与安全性 滚动到最低,找到FreeTube应用,允许打开.

还是不行?

打开终端,输入下面👇命令

sudo spctl --master-disable

然后回车,输入密码后再回车,在 应用程序 路径下找到 FreeTube 应用并 右键 再点击 打开.