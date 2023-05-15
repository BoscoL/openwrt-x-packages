# OpenWrt-X 内置编译包
- [luci-theme-argon](https://github.com/jerrykuku/luci-theme-argon)：主题插件。
- [PassWall](https://github.com/xiaorouji/openwrt-passwall)：科学上网插件。



# 如何使用？

``` shell
# 拉取 packages
git clone https://github.com/BoscoL/openwrt-x-packages.git

# 拷贝至/openwrt/package
sudo cp -R /openwrt-x-packages/luci-theme-argon/ /openwrt/package/luci-theme-argon
sudo cp -R /openwrt-x-packages/passwall /openwrt/package/passwall
```



