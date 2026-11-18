# blivedm

**AG99 依赖修订版**　murphys7017 基于 xfgryujk 的 blivedm 1.1.7 调整了包版本和 HTTP 依赖范围，以适配 AstrBot 直播主持插件。配套版本为 `1.1.7+ag99.1`。 [blivedm 上游](https://github.com/xfgryujk/blivedm) · [配套源码](https://github.com/murphys7017/blivedm/tree/codex/astrbot-http-dependencies)

Python获取bilibili直播弹幕的库，使用WebSocket协议，支持web端和B站直播开放平台两种接口

[协议解释](https://open-live.bilibili.com/document/657d8e34-f926-a133-16c0-300c1afc6e6b)

基于本库开发的一个应用：[blivechat](https://github.com/xfgryujk/blivechat)

## 使用说明

1. 安装本包

    ```sh
    uv add git+https://github.com/xfgryujk/blivedm.git --branch master
    ```

2. 用法参考[web端例程](./sample.py)、[B站直播开放平台例程](./open_live_sample.py)

> [!NOTE]  
> 本包没有发布到PyPI，从PyPI安装会得到错误的版本
