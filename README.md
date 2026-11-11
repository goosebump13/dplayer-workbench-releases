# DPLAYER 运营工作台

Windows x64 本地会员续费与新生跟进工作台。

## 下载与使用

从本仓库 Releases 下载完整的 Windows 分发 ZIP，全部解压后双击“DPLAYER运营工作台.exe”。保留 EXE 和 _internal 文件夹在一起，无需安装 Python、Git 或 GitHub，也无需 GitHub 账号。

本仓库仅用于发布程序和更新信息，不存放会员、新生、收款、数据库或发布私钥。

## 更新

v1.0.0 用户需手动换到 v1.1.0 一次。之后，程序在检测到适用且签名有效的新版本时，在 LOGO 右下方显示“有新版本”。可查看说明、下载校验并安装重启。

当前版本等于最新版本时，提示保持隐藏；网络访问失败不影响原有业务操作。更新前请保存所有编辑，关闭其他正在编辑的工作台窗口。

## 数据

资料保存在当前 Windows 用户的 %LOCALAPPDATA%\DPLAYER\RenewalWorkbench，与程序版本分开。请定期从网页导出 JSON 备份。程序更新不会上传会员资料。

## 适用范围

面向 Windows 10/11 x64 和现代浏览器。已在 Windows 11 上测试，尚未完成干净 Windows 10 机器验收。EXE 尚未进行 Windows Authenticode 签名；内置更新清单签名用于验证更新来源，不等同于 Windows 发布者签名。
