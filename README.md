# CloudJyutping 云粤词

Windows 10/11 x64 网易云同步歌词、粤拼、日语罗马音与 K 歌录制桌面程序。

## 下载

- [最新版本与使用说明](https://github.com/18528279841/CloudJyutping/releases/latest)
- [Windows x64 单文件 EXE](https://github.com/18528279841/CloudJyutping/releases/download/v0.4.10.30/CloudJyutping-0.4.10.30-win-x64.exe)
- [完整源码压缩包](https://github.com/18528279841/CloudJyutping/releases/download/v0.4.10.30/CloudJyutping-0.4.10.30-source.zip)
- [版本信息 JSON](https://github.com/18528279841/CloudJyutping/releases/latest/download/latest.json)

下载 EXE 后运行，无需另行安装 .NET。部分音频分析模型首次使用时按需下载，后续在本机处理。录音、草稿、设置与模型位于本机应用数据目录。

升级时先结束录制并退出程序，再运行新版本。0.4.10.30 尚未内置自动更新；上传版本信息不代表程序已经能自动更新。

本仓库用于版本发布，完整源码在每个版本的附件中。GitHub 自动生成的 Source code 压缩包只包含本发布仓库；请下载名称包含 CloudJyutping 和版本号的 source.zip。

## 验证范围

0.4.10.30 已通过 135 项自动化测试及 Windows 10 启动检查。融合连读的教学语音正例检出为 6/8，不代表真实歌曲准确率；本轮未完成真实歌曲误报率或 Windows 11 实测。详见版本说明。

SHA-256 用于核对文件完整性；当前 latest.json 尚未附加独立发布签名，不应直接作为自动执行更新的信任依据。

第三方组件遵循各自许可证，完整声明位于源码包的 THIRD-PARTY-NOTICES.md 和 licenses 目录。
