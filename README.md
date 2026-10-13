# MoeKoe for fnOS

飞牛 fnOS 应用源（FnDepot 外部源）。

## 安装应用

FnDepot 客户端 → 添加外部源 → 填入本仓库地址：

```
https://github.com/hzs-sama/moekoe-fnos
```

当前提供：**MoeKoe 音乐** —— 酷狗源在线音乐 Web 版（搜索 / 歌单 / 排行 / 歌词 / 每日推荐），Web 部署形态，安装后在飞牛桌面点开即用，默认端口 8095。应用内酷狗扫码登录可同步收藏并解锁高音质。

## 免责声明

本项目为非官方第三方客户端，仅供个人学习、技术研究与交流使用，与酷狗音乐无任何关联；请自觉支持正版。完整条款见 [DISCLAIMER.md](DISCLAIMER.md)，下载/安装/使用即视为已阅读并同意。

## 协议

- 本仓库自产内容：[MIT](LICENSE)
- `apps/moekoe/payload/src/`：[MoeKoeMusic](https://github.com/MoeKoeMusic/MoeKoeMusic) **GPL-2.0**（随目录内 LICENSE 分发；相对上游修改：Dockerfile 基础镜像 node:22-alpine、npm/apk 国内源）。应用图标版权归 MoeKoeMusic 项目
- `apps/moekoe/payload/src/api/`：[KuGouMusicApi](https://github.com/MakcRe/KuGouMusicApi) **MIT**，版权归 MakcRe
