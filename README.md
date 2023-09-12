# Warp deb for Arch Linux

该仓库会为您提供适用于Arch Linux的warp-cli包。

本仓库会先从Cloudflare官方获取适用于Ubuntu Focal的Warp安装包，之后我们会解包，在更改内容后重新打包，使其成为一个可以被Arch Linux利用的deb包。

如果想要在您的计算机上安装该仓库提供的包，您需要先使用pacman安装`dbus`、`glibc`、`nftables`、`libcap`、`libnss_nis`和`dpkg`，然后再执行`sudo dpkg -i path/to/warp-no-depend.deb`。
