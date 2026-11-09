# 大肥鱼 · 桌面宠物（仅发布二进制）

一只会陪你写代码、也会偷偷吃白饭的 Windows 桌面小鲸鱼。

> 本仓库**只用于发布可执行包，不包含源代码**。
> 软件免费分享，请勿倒卖或商用。

## 下载

请到 [Releases](../../releases) 下载最新版本：

- `DaFeiYu-v1.0.2.zip`（约 770MB，Windows 64 位）
- `DaFeiYu-v1.0.2.SHA256.txt`（校验值）

SHA256：

```
740ea9b13c938d04a6c6d55b7075a0392808e2e1e1122e1b09c8eb3ecd8d979e
```

## 使用

1. 下载 zip 并解压到任意目录
2. 双击 `大肥鱼.exe`
3. 首次启动会空约 1 秒，属于正常加载
4. 存档在程序同目录的 `state\pet_state.json`

## 注意

- 仅支持 Windows 64 位
- 未做数字签名，SmartScreen 提示时选「更多信息 → 仍要运行」
- 内存几百 MB 是动作帧缓存，不是泄漏
- 本软件免费分享，请勿倒卖或商用

## 第三方组件

Qt/PySide6（LGPL-3.0）、Python（PSF）、FFmpeg 等，完整许可证随包附带在 `LICENSES\`。
