# BYDKEY-APP · 比亚迪无感钥匙 安装包发布仓库

对外公开的 **APK 发布仓库**：所有版本（含历史版本）都在 [Releases](https://github.com/sageramboleo/BYDKEY-APP/releases) 下载，App 内的「检查更新」也直接读本仓库，匿名可读、匿名可下载。

> 源码仓库 `sageramboleo/BYDKEY-Android` 为私有仓库，只保留代码；安装包统一在本仓库发布。

## 三个版本

| 版本 | 分支 | 包名 | 应用名 | 图标 | 说明 |
|---|---|---|---|---|---|
| 正式版 | `main` | `com.mochen.bydkey` | 比亚迪 | 车头 | 无感钥匙完整功能，推荐普通用户 |
| Root 版 | `root` | `com.mochen.bydkey.root` | 比亚迪 | 银色跑车 | 正式版全部功能 + Root 保活 + 快捷键（单击~六击·长按）+ 外部手势工具指令 |
| Xposed 版 | `xposed` | `com.mochen.bydkey.xposed` | 比亚迪 | 红色跑车 | Root 版全部功能 + 内置 Xposed 模块：免无障碍全局音量键控车（hook 系统框架 + 比亚迪官方 App） |

> Root 版与 Xposed 版都可与正式版并存安装，互不覆盖。两个分支的快捷键均支持音量上/下键的 **单击 / 双击 / 三击 / 四击 / 五击 / 六击 / 长按** 共 7 种触发方式，玻璃质感弹窗自由绑定动作。

## 下载

- 最新版本：[Releases/latest](https://github.com/sageramboleo/BYDKEY-APP/releases/latest)
- 历史版本：[Releases](https://github.com/sageramboleo/BYDKEY-APP/releases) 页逐版本下载

## App 内检查更新

各版本的「关于 / 更新检查」页面直接对接本仓库（GitHub Releases API），有新版本会提示更新日志并给出 APK 直链。
