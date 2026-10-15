# CloudJyutping 云粤词

Windows 10/11 x64 网易云同步歌词、粤拼、日语罗马音与 K 歌录制桌面程序。

## 下载

- [最新版本与说明](https://github.com/18528279841/CloudJyutping/releases/latest)
- [Windows x64 单文件 EXE](https://github.com/18528279841/CloudJyutping/releases/download/v0.4.10.31/CloudJyutping-0.4.10.31-win-x64.exe)
- [完整源码压缩包](https://github.com/18528279841/CloudJyutping/releases/download/v0.4.10.31/CloudJyutping-0.4.10.31-source.zip)

下载后运行，无需另行安装 .NET。部分分析模型首次使用时按需下载，随后在本机分析。录音、草稿、设置和模型都保存在本机。

## 软件内更新

从 0.4.10.31 开始支持。旧版用户先手动下载并换用一次本版；以后在主窗口左下角点击“下载并更新”，完成后重启。默认每天最多自动检查一次，不自动下载或重启。录制、暂停录制、准备及处理录音时会等待，完成后再点“重启并更新”。

更新保留设置、歌词缓存、录音、草稿和模型，只替换 EXE。程序所在文件夹需要可写。下载失败可重试；更新助手保留上一版 EXE，新版未确认主窗口启动时尝试回滚。

客户端验证 RSA-PSS 发布签名和 EXE 的 SHA-256，使用[签名更新清单](https://github.com/18528279841/CloudJyutping/releases/latest/download/update.json)。[普通下载索引](https://github.com/18528279841/CloudJyutping/releases/latest/download/latest.json)不用于自动执行。后续发布必须附带与 EXE 匹配的有效签名清单，流程见完整源码中的 UPDATE-PUBLISHING.md。此签名不是 Windows Authenticode 代码签名。

本仓库用于发布，完整源码在每个版本的附件中。GitHub 自动生成的 Source code 附件仅包含发布仓库；请下载文件名含版本号的 source.zip。

## 验证范围

0.4.10.31 通过 138 项自动化回归与 Windows 10 隔离进程更新测试，并核验两种窗口尺寸的更新界面。未在 Windows 11 或真实麦克风录制中升级；录制保护通过状态测试验证。详细范围及音频模型的既有限制见每版发布说明。

第三方组件许可证见源码包的 THIRD-PARTY-NOTICES.md 和 licenses 目录。发布包不包含用户录音、日志、账户配置或签名私钥。
