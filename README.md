# Tang Red Alert Trainer

Windows 单机修改器。此仓库仅提供程序下载与更新说明，应用源码保留在开发者本地。

## 下载

请到 [最新发布](https://github.com/6494667/TangRedAlertTrainer-Releases/releases/latest) 下载 ZIP 包，解压到可写目录后运行 `TangRedAlertTrainer.exe`。ZIP 包含第三方许可证。

1.1.0 起支持在“日志”页点击“检查更新”，也可勾选“启动时检查更新”。下载后校验文件大小和 SHA256，确认重启后安装，旧程序备份在运行目录 `.updates/backups`。

配置、存档及输出均保存在运行目录。更新 GUI 不会重启游戏，也不会替换正在游戏内加载的 DLL。首次使用本更新通道需手动下载安装新版。

## 发布文件

- `TangRedAlertTrainer-版本-win-x64.zip`：首次安装和完整分发包。
- `TangRedAlertTrainer.exe`：更新器使用的单文件主程序，内含辅助组件。
- `update.json`：更新说明、版本、文件大小与校验值。
- `SHA256SUMS.txt`：发布文件 SHA256 校验清单。

应用源码、调试符号、用户配置、地图存档及日志不通过本仓库发布。第三方许可和归属信息随 ZIP 包提供。