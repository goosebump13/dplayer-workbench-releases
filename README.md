# 续场 · 球员续存工作台

Windows x64 本地会员续费、新生跟进与运营工作台。当前正式版本 **v1.2.0**。

[下载最新 Windows 独立版](https://github.com/goosebump13/dplayer-workbench-releases/releases/latest)

## 下载与使用

下载 `Player-Retention-Workbench-1.2.0-windows-x64.zip`，完整解压后双击“球员续存工作台.exe”。保留 EXE 和 `_internal` 文件夹在一起。无需安装 Python、Git 或注册 GitHub。

双击包内“创建桌面快捷方式.vbs”，即可创建透明底续场图标的桌面入口。`*-update.zip` 与 `update-manifest.json` 供应用更新器使用，新用户请下载完整包。

本版支持按续费动作管理可新增、可改名的文案模板，并在球员详情自动替换姓名；采用雾霾蓝透明底续场品牌。

## 旧用户更新

v1.1.0 用户联网启动后，在 LOGO 右下方发现“有新版本”时点击，查看说明、下载更新，保存全部编辑后安装并重启。原快捷方式继续可用。

v1.0.0 用户需要手动下载完整包。原开发工作台不自动接入分发版数据，如需迁移请先导出 JSON，再到分发版恢复。

无新版或网络失败时提示保持隐藏，本地业务正常使用。更新不会上传会员、新生或收款资料。

## 数据与备份

资料保存在当前 Windows 用户的 `%LOCALAPPDATA%\DPLAYER\RenewalWorkbench`，与程序版本分开。产品更名保留原数据位置；不同 Windows 账户各自保存资料。

更新前先保存修改、关闭其他编辑窗口，并从网页导出 JSON 备份。更新器另创建 SQLite 快照；本机快照不能替代离机备份。

本仓库仅发布程序和更新信息，不存放业务数据库、历史业务备份或发布私钥。

## 适用范围

适用于 Windows 10/11 x64 和现代浏览器。已在 Windows 11 上完成实际 EXE 升级、数据保留与重启测试，并在移除 Python PATH 的条件下运行；尚未在干净 Windows 虚拟机实测。

EXE 尚未进行 Windows Authenticode 签名。内置更新签名用于验证更新来源，不等同于 Windows 发布者签名。
