# UbuToolBox

Ubuntu 桌面工具箱公开安装包，无需 GitHub 登录。

[下载最新版](https://github.com/jronald1024/UbuToolBox-Releases/releases/latest)，选择 `.deb`，或包含安装脚本的分发 `.tar.gz`。在 Ubuntu 上运行：

```sh
sudo apt install -y ./ubutoolbox_0.5.5_all.deb
```

0.5.5 起应用自动优先 GitHub，失败时尝试可选 OneDrive 备用目录；设置提供更新日志。下载校验大小、SHA256 和 Debian 包元数据，确认后才安装，保留管理员认证。

GitHub 仅保留最新十个受管理正式版本，完整历史保存在发布者 OneDrive。完整源码归档继续保存在原私有源码仓库。

本版在 macOS 完成包结构、摘要、更新及发布回归，并验证匿名 GitHub 下载；新版 Ubuntu 图形界面与实际 apt 安装未在本次执行。
