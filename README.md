# PMHQ

> 原仓库：[linyuchen/PMHQ](https://github.com/linyuchen/PMHQ)
> 本仓库是 CyberPi 维护用的 fork / 私有镜像，代码以上游为准。

## CyberPi 使用版本

当前赛博皮使用 **legacy** 组合：

- LuckyLilliaBot：**7.12.14**
- LuckyLillia Desktop：**2.7.2**
- PMHQ：**7.1.1**（macOS arm64）
- QQ：**6.9.86-42941**

旧版 LLBot 7.12.14 使用 **PMHQ 7.1.1**。  
PMHQ 官方 Release 只提供 Linux / Windows；macOS 二进制随旧版 Desktop 分发，本地缓存在 `cyberpi-vendor/lucky-lillia-2.7.2/`。

Pure memory hook for QQNT

## Web UI

Once PMHQ is running, open the Web UI in your browser to inspect sent/received
packets in real time and read the API documentation:

- Packet monitor: `http://127.0.0.1:13000/`
- API docs: `http://127.0.0.1:13000/doc`

The host and port follow `default_host` / `default_port` in the config (default
`127.0.0.1:13000`).

## Configuration

- Configuration file reference: [config.md](./doc/config.md)
