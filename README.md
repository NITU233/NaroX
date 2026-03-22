# NaroX: 一个Android多功能工具集

---
## 关于项目
这个项目一开始是我给自己练手的，顺便做一些对自己有用的功能

## 问题帮助
- [存档编辑 - Permission Denied](docs/help/permission/Help.md)
- [存档编辑 - 不支持自动解密](docs/help/encrypt/Help.md)

## 目前有的功能
- 文件管理器(类似mt管理器的双列模式，方便文件操作)
- 字符串操作(加密解密、哈希处理等功能)
- 实用工具(进制转换、预览网页、汇编转换等功能)
- 图片工具(转换图片到像素画等)
- Minecraft工具(查询史莱姆区块、玩家信息等)
- Minecraft存档解析与NBT编辑器
- 图片格式转换(png、jpg、svg等)
- 压缩包查看与解压
- 文件解析与修改(apk、AXml、elf等)
- 支持Shizuku与root功能
- 终端模拟器
- 插件功能
- ...

项目还在持续开发中，未来会有更多功能！

### 构建项目


构建项目前请在项目的【**[local.properties](./local.properties)**】文件中写入下面的签名信息后才能运行
```properties
SIGN_KEY_STORE_FILE=签名文件路径
SIGN_KEY_STORE_PASSWORD=签名密码
SIGN_KEY_ALIAS=别名
SIGN_KEY_PASSWORD=别名密码
```
开始构建
```shell
# 克隆项目
git clone https://github.com/NITU233/NaroX

# 使用 Gradle 构建 Debug 版本
./gradlew assembleDebug
```

### QQ群:
点击 [![QQ交流群](https://img.shields.io/badge/459206526-blue.svg)](https://qm.qq.com/q/xbYsBm509U)加入QQ群

![软件主页](./img/app_main.webp)