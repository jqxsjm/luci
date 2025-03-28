# OpenWrt LuCI 软件仓库

[![Translation status](https://hosted.weblate.org/widgets/openwrt/-/svg-badge.svg)](https://hosted.weblate.org/engage/openwrt/?utm_source=widget)

## 描述

这是包含 LuCI（OpenWrt 配置界面）的 OpenWrt“luci”-软件接口。

## 用法

此 feed 默认启用。您的 feeds.conf.default（或 feeds.conf）应该包含如下行：
```
src-git luci https://github.com/jqxsjm/luci.git
```

要安装所有包定义，请运行：
```
./scripts/feeds update luci
./scripts/feeds install -a -p luci
```

## API 参考

您可以直接在Github上浏览生成的API文档。

 - [服务器端 Lua API](http://openwrt.github.io/luci/api/index.html)
 - [客户端 JavaScript API](http://openwrt.github.io/luci/jsapi/index.html)

## 发展

可以找到开发和扩展 LuCI 的文档 [在 Wiki](https://github.com/openwrt/luci/wiki)

## 执照

参见 [LICENSE](LICENSE) 文件。
 
## 包装指南

参见 [CONTRIBUTING.md](CONTRIBUTING.md) 文件。

## 翻译状态

使用 [Weblate](https://hosted.weblate.org/engage/openwrt/?utm_source=widget) 而不是直接编辑“*.po”文件。

[![Translation status](https://hosted.weblate.org/widgets/openwrt/-/multi-auto.svg)](https://hosted.weblate.org/engage/openwrt/?utm_source=widget)
