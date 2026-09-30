# 萌册 · 发布仓库

这个仓库只存放 **萌册（MengCe）** 的安装包，供应用内更新读取。源码不在这里。

每个 Release 包含：

- `MengCe-<版本>.apk`：安卓版
- `MengCe-Windows-Setup-<版本>.exe`：电脑版安装程序
- `latest.yml`：电脑版更新清单
- `update.json`：安卓版更新清单

应用会读取最新 Release 里的清单来检查更新，无需手动到这里下载。
